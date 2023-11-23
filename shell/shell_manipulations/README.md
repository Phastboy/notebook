# Shell manipulations

## Overview

In this part we'll talk about how to manipulate directories and files with some commands.

## Wildcards

Shell provides special characters that helps select group of files. These special characters are called `Wildcards`.Some of them include:

- `*`: matches any characters.
- `?`: matches any single character.
- `[characters]`: matches any character that is a member of the set _characters_. It also support poxis character class.
- `[!character]`: matches any character that is not a member of the set _characters_.

**Examples**
- `*`: all filenames.
- `a*`: all filenames that begins with `a`.
- `*b`: all filenames that ends with `b`.
- `a*.txt`: all filenames that starts with `a` and ends with `.txt`.
- `ab??`: any filename that starts with `ab` followed by two or or more characters.
- `[abc]*`: any filename that starts with `a` or `b` or `c` followed by any other characters.
- `[[:upper:]]`: any filename that starts with an uppercase letter. This is an example of character class.
- `BACKUP.[[:digit:]][[:digit:]]`: any filename that begins with `BACKUP` followed by two numbers.
- `*[![:lower:]]`: any filename that does not end with a lowercase letter.

***You can use Wildcards with any command that accept filename arguments***

## Some manipulation commands

### File And Directories Manipulation

- `mkdir`: make directories.
- `rmdir`: remove empty directories.
- `touch`: create empty file.
- `cp`: copy files and directories.
- `mv`: move or rename files.
- `rm`: remove files or directories.
- `find`: search for files in a directory hierarchy.

### Content manipulation

- `cat`: concatenate files and print on the standard output.
- `more`: display the contents of a file in a terminal.
- `less`: opposite of more.
- `grep`: print lines that match patterns.
- `head`: output the first part of files.
- `tail`: output the last part of files.
- `sed`: stream editor for filtering and transforming text.

### Text processing

- `sort`: sort lines of text files.
- `wc`: word count.
- `tr`: translate or delete characters.
- `uniq`: report or omit repeated lines
- `cut`: remove sections from each line of files.

### Permission And Ownership Manipulation

- `chmod`: change file mode bits.
- `chown`: change file owner and group.
- `chgrp`: change group ownership.

### System configuration and information

- `date`: print or set the system date and time
- `cal`: display a calendar
- `du`: estimate file space usage.
- `uname`: print system information.
- `hostname`: show or set system host name.
- `ps`: report a snapshot of the current processes.

### Environment manipulation

- `alias`: create custom shortcuts for commands.
- `export`: set environmental variables.
- `source`, `.`: execute commands from a file in the current shell session.
- `unset`: clear or remove variables.

### File compression and archiving

- `tar`: an archiving utility
- `zip`, `gzip`, `bzip2`: compress or extract files.

