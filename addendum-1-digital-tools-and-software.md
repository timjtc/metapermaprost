---
id: NO-D20240108053852110-1.0-1
aliases:
  - Permaprost Addendum#1 - Digital Tools and Software
---
With the advent of digital formats and powerful computing, it is highly recommended to store notes in digital formats for faster changes and turnaround time for workflows.
# Key Software

Listed below are software that are crucial to adhering to Permaprost.
## Operating Systems

- Microsoft Windows 7 and above
- Linux distros
- macOS
## File Systems

- NTFS in a GPT
- ext4 in a GPT
## Text Editor

- vi, vim, neovim, or any implementations of vi
- nano
- Visual Studio Code
- Obsidian
## Sync and Backup

- Git
# Addons, Modifications and Plugins

- neovim
	- obsidian.nvim ([epwalsh/obsidian.nvim: Obsidian 🤝 Neovim (github.com)](https://github.com/epwalsh/obsidian.nvim))
- Obsidian
	- Core plugins
		- Backlinks
		- Canvas
		- Command palette
		- Daily notes
		- File recovery
		- Note composer
		- Page preview
		- Quick switcher
		- Sync
	- Community plugins
		- Templater
# Naming Conventions

### Kebab Case

A string in Kebab Case is delimited by dashes (-) and looks like this: `this-is-in-kebab-case`.

It is suggested to name files in Kebab Case to maximize interoperability between file systems instead of the conventional file naming that uses white-space characters.
### Snake Case

A string in Snake Case is delimited by underscores (\_) and looks like this: `this_is_in_snake_case`.

Temporary variables or placeholders declared under this system must follow the Snake Case naming.
### Camel Case

A string in Snake Case is delimited by each first letter of the words in the string itself in uppercase, except the very first character. It looks like this: `thisIsInCamelCase`.

Methods, functions or scripts declared under this system must follow the Camel Case naming.
### Pascal Case

A string in Pascal Case is delimited by each first letter of the words in the string itself in uppercase and looks like this: `ThisIsInPascalCase`.

Classes or objects declared under this system must follow the Pascal Case naming.
# Configuration

## Obsidian

- Sync
	- Selective sync
		- Excluded Folders
			- `_metapermaprost/.git`
		- Sync all other types: `TRUE`

# Implementation

## Obsidian

When creating an Obsidian vault, the vault name itself must be in [[#Kebab Case]] and the folder name that will be created for the vault in the file system will also be in the same case.

All folders inside the vault must also be in kebab case, except the configuration folder `.obsidian`, the files of metapermaprost in `_metapermaprost`, or any Git repositories under `.git` used for sync, backup or version control.
### Referencing

Block references (a caret followed by the [[#Short citation name]]) must be provided after each source listed in a Fleeting Note or Literature Note when there is no Reference Note existing for it or if a Reference Note is not necessary for the reference.
## Short citation name

[[permaprost-sysdoc#Reference Notes]] must be named in the manner described by each situation, regardless of key software being used. The methods described below closely resembles how an in-text APA citation is generated.

If the reference is a book, article, journal or a similar sort of publication:
	the last name of the first alphabetical author,
	followed by the initials of its first name in uppercase (resembling a camel case),
	followed by a dash,
	(if there is a second author,
		the last dash is followed by the last name of the second alphabetical author,
		followed by the initials of its first name in uppercase (resembling another camel case),
		followed by a dash
	),
	(if there is more than two authors,
		the last dash is followed by `etal`,
		followed by a dash
	)
	followed by the year of publication,
	followed by the abbreviation of the title of the work (refer to [[#^764429]]),
	and followed by the existing bibliography identifier

If the reference is a media in an online social or multimedia platform:
	the shorthand alias of the channel, uploader, or streamer (refer to [[#^0231cd]]),
	followed by a dash,
	followed by the year, month and date of publishing (in `ISO8601 YYYYMMDD`),
	followed by a dash,
	followed by the unique link identifier of the video
Examples of these platforms are YouTube, Twitch, Facebook, Twitter, TikTok, etc.

If the reference is a movie or film:
	the last name of the director or someone in a similar role as an author,
	followed by the initials of its first name in uppercase (resembling a camel case),
	followed by a dash,
	followed by the year of release or showing,
	followed by a dash,
	followed by the abbreviation of the title of the work (refer to [[#^764429]]),
	followed by the shorthand alias of the studio name (refer to [[#^0231cd]])
Referencing specific chapters or timestamps must be defined as partial references inside the Reference Note and be cited as a part of that.

If the reference is a TV series:
	the last name of the executive producer or someone in a similar role as an author,
	followed by the initials of its first name in uppercase (resembling a camel case),
	followed by a dash,
	(if there is a executive producer,
		the last dash is followed by the last name of the second alphabetical executive producer,
		followed by the initials of its first name in uppercase (resembling another camel case),
		followed by a dash
	),
	(if there is more than two executive producers,
		the last dash is followed by `etal`,
		followed by a dash
	)
	followed by the year of first aired episode,
	(if the series has finished airing and no more seasons are confirmed to follow,
		the last character is followed by the year of last aired episode,
	)
	followed by a dash,
	followed by the abbreviation of the title of the work (refer to [[#^764429]]),
	followed by a dash,
	followed by the shorthand alias of the production company name (refer to [[#^0231cd]])

If the reference is a video game:
	...

**Producing an abbreviation of work title for citations** ^764429

1. Strip all conjunctions from the title.
2. Strip all prepositions from the title.
3. Strip all special characters and symbols such as colons, semicolons, hyphens, and the like.
4. Take the first character of all remaining words (treat numbers or consecutive groups of numbers as a single word) and concatenate them together without delimiters or spaces.

**Producing a shorthand alias for media creator names** ^0231cd

1. If the name is comprised of several words that form something similar to a brand, a person's name, or initials of a person's name delimited by spaces, other special characters, or by cases such as `camelCase` or `PascalCase`,
	1. and if the name can be positively identified by groups of consecutive characters less than 10, use those group of characters, word or name as the shorthand concatenated together.
	2. if it needs to go above 9 characters to be positively identified and if the name can be positively identified by only the first consecutive group of characters, use only the first consecutive group of characters, word or name as the shorthand.
	3. or if the name is known to be abbreviated by the creator itself or its followers, use the abbreviation as the shorthand.
	4. or if the name can be abbreviated even if it's not a popular abbreviation, still use the abbreviation as the shorthand.
2. If the name is comprised of several words that form something similar to a brand, a person's name, or initials of a person's name but it is treated as one word,
	1. if the name is less than 10 characters or letters long, use the whole creator or channel name with all lowercase characters as the shorthand.
	2. if the name is more than 9 characters long, use the group of consecutive characters less than 10 that logically reads as a name or word.