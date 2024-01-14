---
id: <% INDENT_ID = "NO-R" + tp.date.now("YYYYMMDD") + "-${bib_id}" %>
aliases:
---
<%*
NOTE_TYPE = "reference";
NOTE_DIR = "/kmath/" + NOTE_TYPE + "-notes/";
try {
	await tp.file.move(NOTE_DIR + "new-" + NOTE_TYPE + "-note");
} catch (e) {
	await tp.file.move(NOTE_DIR + "new-" + NOTE_TYPE + "-note-" + tp.file.creation_date("YYYYMMDDTHHmmssSSS"));
}
-%>
Author1LastName, Author1FirstName; Author2LastName, Author1FirstName (Year).
_Title_ (nth ed.). Publisher.

[hdl:: [0000/uc0.b0000000](link)]
[oclc:: [10000000](link)]

# Partial References

1. pp. 1-2 ["Section Title"] ^pp1-2
	<< APA Citation >>
# Associated External Links

