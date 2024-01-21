---
id: NO-D20230820064734723-1.0
aliases:
  - Permaprost System Documentation
  - PermaprostSysdoc
---
**Personal Management and Productivity System (Permaprost) - System Documentation**

# Definition of Terms

Paper note - All notes written on paper with an ink pen or pencil is considered a paper note.
YAML front matter - A structure for defining metadata on hypertext or markup files.
	Aliases: YFM
Zettelkasten note - A single unit or entity of note that is either one of three types in accordance to the Zettelkasten concept.
	Aliases: ZK note
Personal Knowledge Management
ISO 8601

+++

# Methodology

This document, note, or article, whichever way it is perceived, is recursive. The concepts and methods mentioned here can be applied to this entity. To aid in conveniently setting rules and conventions for this system itself, a metapermaprost must exist to contain this document itself, its addendums, and other metadata that sets a stable fundamentals for Permaprost.
# Knowledge Management and Thought Collection (KMATH)

KMATH defines how knowledge, thoughts, ideas, and data are captured or collected, how are they compiled to a specific structure, and where are they stored.
Notes are assigned a unique ID as per INDENT with the root classification `NO` followed by variables that describe the medium of persistence and other classification mentioned below.
## Units of Knowledge

- ~~Information - general facts learned about something or from someone~~
- ~~Thought -~~ 
- ~~Concept/theory -~~ 
- ~~Data - technical stuff, math, analytical~~
- ~~Principle~~
- ~~Idea~~
## Zettelkasten Note-Taking

Notes that follow the Zettelkasten flow.
### Fleeting Notes

Raw ideas (information, thoughts, data, etc.) gathered or generated must be recorded in Fleeting Notes. Each record here can be written as raw as possible while permitting the use of jargons, abbreviations, contractions, slang or any other form of informal writing to scribe thoughts as quick and as fresh as possible.

Some common scenarios of usage:
- When sudden realization, an epiphany or random thoughts strike and must be captured as raw and soon as possible to avoid loss of idea.
- When you see or hear a valuable quote that encompasses wisdom and you feel like you can use or apply that somewhere but not sure where or when. 

A Fleeting Note might or might not point to references and has no specific structure.
### Literature Notes

Writing deducted information, thoughts or ideas whenever consuming any literature, online content, multimedia or any medium of information transfer must be written in a Literature Note.
The writing style in a Literature Note must emphasize the key ideas presented in the content. It still involves writing the raw ideas in one's words, but leaves out the informality and highly subjective nature of Fleeting Notes.

Only the sources or content where the idea was inspired or implied from must be listed at the end of the note and follow the suggested format for citing references. As such, the DRF dictates that the only allowed references are those in the context plane.
### Fragmented Notes

Writing any atomic thought about something, information or definition falls under Fragmented Notes. Anything contained within must not deviate from the topic or reference anything, even something related to it. A Fragmented Note must make its statement or thesis clear as brief as possible. 

It must either contain references to direct sources where the current idea was derived or implied from, or by the Literature Note that explores such direct sources. To further prove its level of absoluteness, it must refer to auxiliary ideas that support or state a similar thesis that is also already atomic or fragmented.
### Flow

~~An NO-E can evolve into an NO-F when trying to normalize, sanitize or even break down the raw information or thought from the NO-E. An NO-F can be evolved into a separate NO-L when a deeper study into the thought or information is warranted and sufficient sources are found or encountered to back this study. An NO-L can evolve into an NO-R when sufficient testing or real-world data provides insights or proof how a new information can be applied and turned into wisdom.~~
~~An NO-L can also be broken down into various NO-Fs when several information is presented in that NO-L that can be related or unrelated to each other and can be further divided into their atomic form.~~
## Note Relations

### Reference

A reference is a general form of mentioning, relating or linking ideas. It can point to an idea, note, literature, media or any form of content.
### Directional Relation Framework (DRF)

This is an implementation of the Zettelkasten Compass by Fei, presented in one of Vicky Zhao's YouTube video ([[NO-L20240114005847784.zettelkasten-obsidian-workflow-by-vicky-zhao#^d3256d|2023 Zettelkasten Obsidian Workflow by Vicky Zhao]]). There are four arbitrary directions, axes or planes a relation to other ideas or notes can go:
- **Up / Context**: Where the idea comes from? What is/are the source content of the idea? What inquiries does it satisfy?
- **Rear / Auxiliary**: What other ideas or references support this idea? What are ideas with similar statement or thesis?
- **Right / Contrary**: What ideas are opposite to this?
- **Down / Next**: Where this idea leads to? What conclusion or action can this imply?

The DRF is only strongly recommended to be used in Fragmented Notes, as they require clear interconnection of ideas. Literature Notes or Fleeting Notes may or may not use this framework, but must still adhere to its nature of referencing its sources in any method, if required.
#### Source

A Source is a form of reference that points to the literature, media, or any form of content where the idea was implied. Using the DRF, a Source Reference can only be in the context plane and must point to a content or a note that is not atomic or fragmented. Sources must be marked by preceding with a greater than symbol `>`, equally appearing inside quotes in markdown.
#### Auxiliary

An Auxiliary Reference points to an idea that supports the absoluteness or states a similar thesis to the current idea. This reference must point to an idea or note that is already fragmented. An Auxiliary Reference, in its name itself, resides in the auxiliary plane.
#### Link

A link is a general abstraction of a reference that can point in any plane. It can point to a fragmented idea that is contrary or stands in opposition to the current idea. It can also point to another context or question, or to a conclusion or action that would formulate or resolve upon assuming the absoluteness of the idea.
## Convenience of Searching and Retrieving Notes

### Tags

`#context`

`#auxiliary`
`#auxiliary/anecdote`
`#auxiliary/experience`
`#auxiliary/quote`
`#auxiliary/study`
`#auxiliary/data`

`#hollow`
`#verify`
## Abstract Note Types

Notes that may or may not follow the Zettelkasten flow.
### Daily Journal

A Daily Journal is a manifestation of a Fleeting Note. Ideas generated or gathered throughout a day must be placed in a Daily Journal and be recorded in a raw form. It is recommended to use a bullet format for each block of idea or event. There is also no restraint to what a Daily Journal might comprise, each block can be a whole Fleeting or Literature Note that can be later moved to a separate note markdown file.
### Quick Notes

quick notes
### Illustrative Notes

Drawings and stuff...
### Technical Notes

Procedures and stuff...
### Template Notes

Defines how other notes are structured.
### Reference Notes

When a source or reference needs to be stored in a separate note for a more detailed citation, especially when there is a need for an APA or MLA listing, it must be stored in a separate Reference Note instead of being an entry in the References or Sources section. Reference Notes will have the same naming convention as a citation entry in a block.

This is especially true when referencing a content that would take a long time to consume, only a portion of such content is consumed or is to be consumed, or only that small portion is useful for implying the idea in a note. Examples of these are publications, books, novels or academic journals that might be too lengthy to consume and also has different editions, or also a TV series, movie or film where only a short timestamp of it contains the implication of the idea. This is in contrast to, say for example, a YouTube video or short that can be contained in a single link and only have a one version of itself.
## Note Evolution and Displacement

When a block inside a note is moved to a different or separate note, a link must point to the new note in place of the whole block of content that was previously there.
When a note must evolve into a different type, a new INDENT ID must be generated to replace the previous ID, or just create a new note altogether and move the content into the new one. Whichever is performed, the evolved note must mention the...
## Note Persistence

The following defines where notes are stored or written.
### Paper Notebooks

Notes written on a piece of paper are considered as Paper Notes. Generally, it is more recommended writing notes in digital format for the convenience of synchronization across devices, faster idea collection, and faster lookup. However, there are special cases where a paper notebook is necessary, especially in the risk of loss, corruption or destruction of digital data, or when an instruction specifically needs paper notebooks.

Digital notes with paper counterparts or copies must state a callout in the end of the note that any revision in the note warrants a rewrite of the paper copy.
#### Initialization

A paper notebook must have already been procured and ready for writing. A description string for the purpose of use for the notebook must be ideated first. This string will be the input to a CRC-32 hash algorithm to determine the substring of the ID. Then, the Paper Notebook ID must be created adhering to the following:
```
---
INDENT: DEF
syntax: "??-${crc32_nb_desc}}"
root: "NB"
vars:
  crc32_nb_desc:
    desc: "Output of the CRC-32 hash of the description of use for the notebook"
    format: "string"
...
```

The first page of the notebook must contain the following text:

> This paper notebook has been initialized under Personal Management and Productivity System - Knowledge Management and Thought Collection (Permaprost-KMATH). All notes contained or will be written herein must adhere to the methodologies and workflows stated under Permaprost-KMATH.
> Refer to `${latest_sysdoc_indent}` for more details.
> 
> Author: `${name}`
> Paper Notebook ID: `${indent}`
> Description: `${desc}`

#### Indexing

INDENT:
`NP-${nb_index}${pagenumber}#`
### Digital Formats

Notes created and stored in any computer are considered notes in Digital Format. All digital notes will have an INDENT root classification of `NO`. Plain-text formats are recommended due to interoperability and simplicity.

As of writing (2023-08-21), Obsidian is used to store notes in Markdown (.md) format.
#### Indexing with INDENT

*Fleeting Notes*
```
INDENT DEFINITION
{
	"syntax": "??-F#",
	"root": "NO",
	"index": "iso8601datetime_YYYYMMDDHHmmssSSS"
}
```

*Daily Journal*
```
INDENT DEFINITION
{
	"syntax": "??-F#J",
	"root": "NO",
	"index": "iso8601date_YYYYMMDD"
}
```

*Literature Notes*
```
INDENT DEFINITION
{
	"syntax": "??-L#",
	"root": "NO",
	"index": "iso8601datetime_YYYYMMDDHHmmssSSS"
}
```

*Fragmented Notes*
```
INDENT DEFINITION
{
	"syntax": "??-G#",
	"root": "NO",
	"index": "iso8601datetime_YYYYMMDDHHmmssSSS"
}
```

*Quick Notes*
```
INDENT DEFINITION
{
	"syntax": "??-Q#",
	"root": "NO",
	"index": "iso8601datetime_YYYYMMDDHHmmssSSS"
}
```

*Illustrative Notes*
```
INDENT DEFINITION
{
	"syntax": "??-I#",
	"root": "NO",
	"index": "iso8601datetime_YYYYMMDDHHmmssSSS"
}
```

*Technical Notes*
```
INDENT DEFINITION
{
	"syntax": "??-T#",
	"root": "NO",
	"index": "iso8601datetime_YYYYMMDDHHmmssSSS"
}
```

*Reference Notes*
```
INDENT DEFINITION
{
	"syntax": "??-R#-${bib_id}",
	"root": "NO",
	"index": "iso8601datetime_YYYYMMDD",
	"vars": 
	{
		"bib_id": 
		{
			"desc": "A unique identifier of an existing standard like ISBN, DOI, HDL, etc",
			"format": "alphanumeric"
		}
	}
}
```
## Data and Information Security


# Structured Data

Data that is stored with a specific structure or format falls under this section.


Plain-text notes must not contain PII...

# Indexing and Identification (INDENT)

INDENT defines how identifiers are defined and assigned to various entities as uniquely as possible.
## Syntax Definitions
### Root classification
All IDs start with two alphanumerical characters that indicate root classification.

### Subclassification
Asterisks (\*) indicate a variable character for subclassifications that can also be perceived as a wildcard. Assigning an item to a root classification without any subclassification must fill wildcards with zero (0). 

### Variable
Dollar signs ($) indicate a variable defined by a formula or a list of possible values. 

### Index
Pound or hash signs (#) indicate where the indexing characters should begin.

### Delimiter
Various parts of an ID should be separated by a delimiter to define a clear and logical structure. The default delimiter is a dash (-) (45 in ASCII, U+002D in Unicode).

## Documented Root IDs

### 0T -- Test ID
Syntax: `0T*#`

Test IDs are meant to index test or temporary entities.

Subclassifications:
	`0TU#` - Unique strict
		Index values with this subclassification must have uniqueness, preferably by generating random data to reduce data retention overhead.
	`0TN#` - Non-unique
		Index values with this subclassification can have a loosely generated values for temporary use.

### TK - Task

**Jira-based TWM**
Syntax: `TK***-#`

Markdown-based TWM

### NB -- Paper notebook
Syntax: `NB-#`
Indexing variables can consist of alphabets that can denote the purpose or category of the notebook.

### NP -- Note on paper
Syntax: `NP-*#`

Subclassifications:
	`NP-F#` - ZK fleeting note written on paper
	`NP-L#` - ZK literature note written on paper
	`NP-D#` - ZK distilled/permanent note written on paper

Indexing:
	All `NP-*#` IDs must follow an incremental indexing. Several pages at the start of a paper notebook must be designated to contain the index table.
	The index table must be structured with the following columns:
		- ID
		- Pages
		- Description
	Each row in the index table must contain the notes that are instantiated.

Note Instantiation:
	A note can be created by writing any content, knowledge, thought or idea on a page. Make sure to reserve a space or some lines dedicated to note metadata.
+++

### NO -- Note on digital platforms
Syntax: `NO-*#`

Subclassifications:
	`NO-J#` - ZK fleeting note as a daily journal
		Indexes for NOJ notes must be a date and time in the format of `YYYYMMDD` implemented in JavaScript as per ISO 8601.
	`NO-F#` - ZK fleeting note
	`NO-L#` - ZK literature note
	`NO-D#` - ZK rationalized or permanent documentation note
	`NO-Q#` - Notes with structured data for quick lookups (quick notes)
	`NO-H#` - Hand-drawn or hand-written notes (convert all NOH to NOI)
	`NO-I#` - Illustrative notes

Indexes for notes with subclassification NOF, NOL and NOD must be a date and time in the format of `YYYYMMDDHHmmssS` implemented in JavaScript as per ISO 8601.
+++

### NT -- Note template
Syntax: `NT-#`

Indexes must be a date and time in the format of `YYYYMMDD`

### PW -- Prototyping wire
Syntax: `PW-{$type}{$color}{$length}-#`

Variable `{$type}`:
	`S` - Solid wire
	`N` - Connecting wire
	`J` - Jumper

Variable `{$color}`:
	`S` - Solid wire

Variable `{$length}`:
	The length of the wire in centimeters divided by 10.
	
### E0 - Coursera activities

### E1 - UE activities

### CR - Cloud computing resource
Syntax: `CR*#`

### TS -- Time states
Syntax: `TS*`

++++++

# Task and Workflow Management (TWM)

A task is an atomic entity of work or job that needs to be done.

## States

Tasks have different states that indicate their status and what action must be performed upon the task. 
- TS1_TO_DO
	 The task is queued for work.
- TS2_IN_PROGRESS
	 Work is being performed upon the task.
- TS3_DONE
	 The task is completed and requires no further work.
- TS4_FAILED
	 The task has failed under certain criteria, deadline, or standards and requires no further work.
- TS5_CANCELLED
	 The task has been cancelled and requires no further work.
- TS6_ARCHIVED
	The task is no longer relevant and the data or information is now trivial for references.
## Projects

Tasks can be grouped under Projects to set a clear goal for that group of tasks.
## Dependencies and Child Tasks

dependencies...
## Priority

TP1 - Urgent
TP2 - High
TP3 - Normal
TP4 - Low
TP5 - Trivial

## Software and Tools

As of writing, the primary software used to track all tasks is Jira. (2023-08-21)

**Identifier**

Each task is assigned an ID upon creation. Rules for this are defined under INDENT.

--

# Time Adherence Discipline (TAD)
- All activities related to a certain project, job or goal must be documented with a time sheet.
- Software currently used: Toggl Track
--

# Contact Relations Management (CRM)
- x
--

# Personal Budget Management & Financing (PENBUMF)

## Recursive Expenses

Expenses that are made per unit of time to keep or maintain a specific service or product are defined as Recursive expenses.

**Tracking**

All Recursive expenses are to be recorded as a structured data as per KBATH and INDENT. Recursive expenses will be assigned a unique ID with root classification FR, and thus each Recursive expense will be referred to as an FR (plural FRs) anywhere under this section for convenience.

```
INDENT DEFINITION
{
	"syntax": "??-$$$${yr_start}$${mo_rec}#",
	"root": "FR",
	"vars": 
	{
		"yr_start": 
		{
			"desc": "Year when the recursive expense started"
		},
		"mo_start": 
		{
			"desc": "Month when the recursive expense started"
		}
	},
	"index": "ai"
}
```

--

# Tools & Software Used
- Obsidian - knowledge management
- OneNote - where old notes are/obsolete
- Notion - ??
- Asana - prospect software for task management?
- Toggl Track - time tracking / productivity adherence

+++

# Version Control

Main sysdoc
```
INDENT DEFINITION
{
	"syntax": "??-X$$$$$$$$$$$$$$$$${dt_created}-MP${ver_num}.${mrev_num}",
	"vars": 
	{
		"dt_created": 
		{
			"desc": "Date and time created",
			"format": "YYYYMMDDHHmmssSSS"
		},
		"ver_num": 
		{
			"desc": "Version number",
			"format": "%d"
		},
		"mrev_num": 
		{
			"desc": "Minor revision number",
			"format": "%d"
		}
	}
}
```

Addendums
```
INDENT DEFINITION
{
	"syntax": "NO-D$$$$$$$$$$$$$$$$${dt_created}-MP${ver_num}.${mrev_num}-${ad_num}",
	"vars": 
	{
		"dt_created": 
		{
			"desc": "Date and time created",
			"format": "YYYYMMDDHHmmssSSS"
		},
		"ver_num": 
		{
			"desc": "Associated sysdoc version number",
			"format": "%d"
		},
		"mrev_num": 
		{
			"desc": "Associated sysdoc minor revision number",
			"format": "%d"
		},
		"add_num": 
		{
			"desc": "Addendum number",
			"format": "%d"
		}
	}
}
```

# Addendums

[[addendum-1-digital-tools-and-software|Permaprost Addendum#1 - Digital Tools and Software]]
