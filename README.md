# Code for Assignment 1 for ILSE, 04-801 B2, Fall 2022

<br/>

## Name : findgrep Bash Script
## Author : Okemawo Aniyikaiye Obaodfin (OAO)
## Date : 03 November 2023
### Description : 
### Recursively searches files in and below a given directory (by default, the current directory) for a specified regular expression. By default, the search will examine only C and C++ files—that is, those that end in .c, .cpp, h, or .hpp—but this can be overridden via command line options. The script returns an exit code of 1 when an eror occurs and an exit code of 0 when it executes successfully. You can observe the usage details about the findgrep script along with its syntax.

<br/>
<br/>

### findgrep [options]  "egrep-pattern"

<br/>

###     Options can be one or more of:
###       --c                   C mode (the default): search files ending in .c, .h, .cpp and .hpp
###       --py                  Python mode: search files ending in .py, .json, and .xml
###       --text                Text mode: search files ending in .txt, .texi, .md, or beginning with the name README.
###       --all                 Look at all files, not just C/C++ files
###       --help                Print this usage message and exit
###       -i | --insensitive    Perform case insensitive search (default is case sensitive)
###       --top <rootdir>       Set the root directory of the search; default is cwd
###       --up                  Set the root of the search to parent of cwd; equivalent to “--top=..”
