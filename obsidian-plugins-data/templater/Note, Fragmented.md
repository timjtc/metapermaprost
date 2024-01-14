---
id: <% INDENT_ID = "NO-G" + tp.date.now("YYYYMMDDHHmmssSSS") %>
aliases:
---
<%*
NOTE_TYPE = "fragmented";
NOTE_DIR = "/kmath/" + NOTE_TYPE + "-notes/";
try {
	await tp.file.move(NOTE_DIR + INDENT_ID + ".new-" + NOTE_TYPE + "-note");
} catch (e) {
	await tp.file.move(NOTE_DIR + INDENT_ID + ".new-" + NOTE_TYPE + "-note-" + tp.file.creation_date("YYYYMMDDTHHmmssSSS"));
}
-%>
# Idea


# References

## △ / Up / Context


## ⦻ / Rear / Auxiliary


## ⊙ / Ahead / Contrary


## ▼ / Down / Next

