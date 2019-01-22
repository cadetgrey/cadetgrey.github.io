---
layout: subpage
---

## Introduction to the Command-line Course

A course to help demystify the intimidating black box with the running text, and to clarify a range of basic but not immediately obvious technicalities.

## Week 1: Introduction to Command-Line Environments

Binary/text distinction

MAN is worth considering as an alternative to alt+tabbing over to google documentation every three minutes

## Week 2: Navigating a Unix System

#### Basic filesystem commands

* **ls** for displaying the contents of a directory
* **cd** to change directory
* **pwd** to display path of current directory

* **mkdir** for creating directories
* **rmdir** for deleting empty directories
* **cp** for copying files or directories
	* usage: cp *[options]* [source] [destination]
	* option *-r* (for *recursion*) required for succesfully copying directories
* **rm** for removing files or directories
	* again *-r* for directories
* **du** for checking the size (**d**isk **u**sage) of a file or directory
* **chmod** to modify...

#### Permissions

**chmod** usage:

`chmod [options] [mode] [target]`

Wherein mode can be expressed either through [octal](https://en.wikipedia.org/wiki/File_system_permissions#Numeric_notation) or [symbolic](https://en.wikipedia.org/wiki/File_system_permissions#Symbolic_notation) notation.

## Week 3: Corpus Processing

| command | functionality 
| ---     | ---           
| grep    | searching for patterns in a file
| sed     | transforming text in a file based on matched patterns
| tr	  | changing or deleting characters in a file
| uniq    | identifying, removing, and counting duplicate lines

## Week 4: Scripting and Unix Configuration Files

## Week 5: Installing and Running Programs

## Week 6: Version Control
