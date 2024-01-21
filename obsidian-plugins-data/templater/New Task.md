---
description: 
status: TS1_TO_DO
due: 
priority: 
tags: 
aliases:
---
<%* 
// CONFIG: below are the only values you are allowed to change
// PROJECT_METAFILE = "_twm_prj_meta_99";
JS_TIMEOUT = 75;
// END OF CONFIG

PROJECT_METAFILE = await tp.system.suggester(["Personal", "Veriflex", "UE_CPE_2023S2", "ΩTmpProj"], ["_twm_prj_meta_01", "_twm_prj_meta_20", "_twm_prj_meta_82", "_twm_prj_meta_99"]);
meta_file = await tp.file.find_tfile(PROJECT_METAFILE);

project_id = app.metadataCache.getFileCache(meta_file).frontmatter["prj_id"];
project_name = app.metadataCache.getFileCache(meta_file).frontmatter["name"];
last_id = app.metadataCache.getFileCache(meta_file).frontmatter["last_id"];

int_next_id = parseInt(last_id) + 1;
next_id = int_next_id.toString();

indent_id = "TK-" + project_id + next_id;
task_dir = "/twm/tasks/" + project_id + "-" + project_name + "/";

let desc = "New template task " + indent_id;
let due = tp.date.now("YYYY-MM-DD");
let prio = "TP3_NORMAL";

setTimeout(() => { 
	app.fileManager.processFrontMatter(tp.config.target_file, frontmatter => { 
		frontmatter["description"] = desc
		frontmatter["due"] = due
		frontmatter["priority"] = prio
	})
}, JS_TIMEOUT); // the reason for the timeout is to let the template complete first

try {
	await tp.file.move(task_dir + indent_id);
	app.fileManager.processFrontMatter(meta_file, frontmatter => { 
		frontmatter["last_id"] = next_id
	});
} catch (e) {
	await tp.file.move(task_dir + indent_id + " " + tp.file.creation_date("YYYYMMDDTHHmmssSSS"));
}
-%>
# Remarks


# Dependencies and Child Tasks


# Related Notes

