# Batch

![License-MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Docs-Passing](https://img.shields.io/badge/Docs-Passing-green.svg)

[中文](docs/README-CN.md) | English

A Batch help document.

## Generate

Open the CMD program and execute the following command.

```Batch
help > temp_File

grep -o -E "^[A-Z]*" temp_File > filter_File

for /f %i in (filter_File) do cmd /c %i /? > Command\%i

del /q temp_File && del /q filter_File
```

## Index

|     Command     |     Description     |
| :-------------- | :------------------ |
| [ASSOC](Command/ASSOC) | Displays or modifies file extension associations. |
| [ATTRIB](Command/ATTRIB) | Displays or changes file attributes. |
| [BREAK](Command/BREAK) | Sets or clears extended CTRL+C checking. |
| [BCDEDIT](Command/BCDEDIT) | Sets properties in boot database to control boot loading. |
| [CACLS](Command/CACLS) | Displays or modifies access control lists (ACLs) of files. |
| [CALL](Command/CALL) | Calls one batch program from another. |
| [CD](Command/CD) | Displays the name of or changes the current directory. |
| [CHCP](Command/CHCP) | Displays or sets the active code page number. |
| [CHDIR](Command/CHDIR) | Displays the name of or changes the current directory. |
| [CHKDSK](Command/CHKDSK) | Checks a disk and displays a status report. |
| [CHKNTFS](Command/CHKNTFS) | Displays or modifies the checking of disk at boot time. |
| [CLS](Command/CLS) | Clears the screen. |
| [CMD](Command/CMD) | Starts a new instance of the Windows command interpreter. |
| [COLOR](Command/COLOR) | Sets the default console foreground and background colors. |
| [COMP](Command/COMP) | Compares the contents of two files or sets of files. |
| [COMPACT](Command/COMPACT) | Displays or alters the compression of files on NTFS partitions. |
| [CONVERT](Command/CONVERT) | Converts FAT volumes to NTFS.  You cannot convert the current drive. |
| [COPY](Command/COPY) | Copies one or more files to another location. |
| [DATE](Command/DATE) | Displays or sets the date. |
| [DEL](Command/DEL) | Deletes one or more files. |
| [DIR](Command/DIR) | Displays a list of files and subdirectories in a directory. |
| [DISKCOMP](Command/DISKCOMP) | Compares the contents of two floppy disks. |
| [DISKCOPY](Command/DISKCOPY) | Copies the contents of one floppy disk to another. |
| [DISKPART](Command/DISKPART) | Displays or configures Disk Partition properties. |
| [DOSKEY](Command/DOSKEY) | Edits command lines, recalls Windows commands, and creates macros. |
| [DRIVERQUERY](Command/DRIVERQUERY) | Displays current device driver status and properties. |
| [ECHO](Command/ECHO) | Displays messages, or turns command echoing on or off. |
| [ENDLOCAL](Command/ENDLOCAL) | Ends localization of environment changes in a batch file. |
| [ERASE](Command/ERASE) | Deletes one or more files. |
| [EXIT](Command/EXIT) | Quits the CMD.EXE program (command interpreter). |
| [FC](Command/FC) | Compares two files or sets of files, and displays the differences between them. |
| [FIND](Command/FIND) | Searches for a text string in a file or files. |
| [FINDSTR](Command/FINDSTR) | Searches for strings in files. |
| [FOR](Command/FOR) | Runs a specified command for each file in a set of files. |
| [FORMAT](Command/FORMAT) | Formats a disk for use with Windows. |
| [FSUTIL](Command/FSUTIL) | Displays or configures the file system properties. |
| [FTYPE](Command/FTYPE) | Displays or modifies file types used in file extension associations. |
| [GOTO](Command/GOTO) | Directs the Windows command interpreter to a labeled line in a batch program. |
| [GPRESULT](Command/GPRESULT) | Displays Group Policy information for machine or user. |
| [GRAFTABL](Command/GRAFTABL) | Enables Windows to display an extended character set in graphics mode. |
| [HELP](Command/HELP) | Provides Help information for Windows commands. |
| [ICACLS](Command/ICACLS) | Display, modify, backup, or restore ACLs for files and directories. |
| [IF](Command/IF) | Performs conditional processing in batch programs. |
| [LABEL](Command/LABEL) | Creates, changes, or deletes the volume label of a disk. |
| [MD](Command/MD) | Creates a directory. |
| [MKDIR](Command/MKDIR) | Creates a directory. |
| [MKLINK](Command/MKLINK) | Creates Symbolic Links and Hard Links |
| [MODE](Command/MODE) | Configures a system device. |
| [MORE](Command/MORE) | Displays output one screen at a time. |
| [MOVE](Command/MOVE) | Moves one or more files from one directory to another directory. |
| [OPENFILES](Command/OPENFILES) | Displays files opened by remote users for a file share. |
| [PATH](Command/PATH) | Displays or sets a search path for executable files. |
| [PAUSE](Command/PAUSE) | Suspends processing of a batch file and displays a message. |
| [POPD](Command/POPD) | Restores the previous value of the current directory saved by PUSHD. |
| [PRINT](Command/PRINT) | Prints a text file. |
| [PROMPT](Command/PROMPT) | Changes the Windows command prompt. |
| [PUSHD](Command/PUSHD) | Saves the current directory then changes it. |
| [RD](Command/RD) | Removes a directory. |
| [RECOVER](Command/RECOVER) | Recovers readable information from a bad or defective disk. |
| [REM](Command/REM) | Records comments (remarks) in batch files or CONFIG.SYS. |
| [REN](Command/REN) | Renames a file or files. |
| [RENAME](Command/RENAME) | Renames a file or files. |
| [REPLACE](Command/REPLACE) | Replaces files. |
| [RMDIR](Command/RMDIR) | Removes a directory. |
| [ROBOCOPY](Command/ROBOCOPY) | Advanced utility to copy files and directory trees |
| [SET](Command/SET) | Displays, sets, or removes Windows environment variables. |
| [SETLOCAL](Command/SETLOCAL) | Begins localization of environment changes in a batch file. |
| [SC](Command/SC) | Displays or configures services (background processes). |
| [SCHTASKS](Command/SCHTASKS) | Schedules commands and programs to run on a computer. |
| [SHIFT](Command/SHIFT) | Shifts the position of replaceable parameters in batch files. |
| [SHUTDOWN](Command/SHUTDOWN) | Allows proper local or remote shutdown of machine. |
| [SORT](Command/SORT) | Sorts input. |
| [START](Command/START) | Starts a separate window to run a specified program or command. |
| [SUBST](Command/SUBST) | Associates a path with a drive letter. |
| [SYSTEMINFO](Command/SYSTEMINFO) | Displays machine specific properties and configuration. |
| [TASKLIST](Command/TASKLIST) | Displays all currently running tasks including services. |
| [TASKKILL](Command/TASKKILL) | Kill or stop a running process or application. |
| [TIME](Command/TIME) | Displays or sets the system time. |
| [TITLE](Command/TITLE) | Sets the window title for a CMD.EXE session. |
| [TREE](Command/TREE) | Graphically displays the directory structure of a drive or path. |
| [TYPE](Command/TYPE) | Displays the contents of a text file. |
| [VER](Command/VER) | Displays the Windows version. |
| [VERIFY](Command/VERIFY) | Tells Windows whether to verify that your files are written correctly to a disk. |
| [VOL](Command/VOL) | Displays a disk volume label and serial number. |
| [XCOPY](Command/XCOPY) | Copies files and directory trees. |
| [WMIC](Command/WMIC) | Displays WMI information inside interactive command shell. |

## License

[MIT](LICENSE)
