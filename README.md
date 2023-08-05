# Reading Notes.

Hi Iam zaid izzeldden, i have 27 years old, i graduate from hashemite university with a major of mechanical engineering, after working in this feild more than 10 months , i realized it wasnt right fit for me, i have always been passionate about learning computer sience and software programming , i hope to develop my self in this field. 

 we learned a about how to get familier with basic git commands,
how to create repositories and clone it to local machine, and update on local version, commit it and push it to main branch  
---
-  Code 102 - Intro to Software Development
+  Code 201 - Foundations of Software Development
*  Code 301 - Intermediate Software Development
-  Code 401 - Advanced Software Development

---
##  SQL :
by practising with sql bolt website , i became familiar with most of sql queries which is 
- selecting from tables 
+ sorting datat 
* ordering data 
- creating tables
+ altering in tables 
* droping tables

![](./asset/sql%20exr_1.png) ![](./asset/sql%20exr_2.png) ![](./asset/sql%20exr_3.png) ![](./asset/sql%20exr_4.png) ![](./asset/sql%20exr_5.png) ![](./asset/sql%20exr_6.png) ![](./asset/sql%20database%20exr_13.png) ![](./asset/sql%20database%20exr_14.png) ![](./asset/sql%20database%20exr_15.png) ![](./asset/sql%20database%20exr_16.png) ![](./asset/sql%20database%20exr_17.png) ![](./asset/sql%20database%20exr_18.png)

---
## Command Lines (terminal)

- the command line : The command line is a text-based interface where commands are entered by typing. It provides a prompt, and as you type commands, the feedback is in text form.

 Commands are entered as follows: the command itself, followed by command line arguments (options) separated by spaces. Options modify command behavior and typically start with a dash (-).

 Most commands generate output, which is displayed immediately after executing the command. After a command completes, the terminal presents a new prompt for the next command.

 Instructions for opening a terminal on different operating systems are given, such as using the "Terminal" application on Mac or searching for it in Linux. For Windows, an SSH client like PuTTY is suggested for remote access.

 + Basic Navigation : The "pwd" command in Linux shows your current location, known as the working directory. It helps you avoid getting lost while using the terminal. Remember to use it regularly.


The "ls" command in Linux lists the contents of a directory. It can be used with various options and locations. The basic format is:

ls: Lists the contents of the current directory.
ls -l: Performs a long listing, displaying details like permissions, owner, size, and modification time.
ls /etc: Lists the contents of the "/etc" directory.
ls -l /etc: Provides a long listing of the "/etc" directory's contents.
In a long listing:

The first character indicates file type ( '-' for normal file, 'd' for directory).
The following 9 characters represent permissions.
Subsequent fields show owner, group, size, modification time, and name.
Using "ls" helps you explore directories and files effectively.

This page explains the concepts of absolute and relative paths in the context of a hierarchical file system, specifically under Linux. The root directory is at the top of the hierarchy and is denoted by a forward slash (/).

_ Absolute Paths: These paths specify a file or directory's location starting from the root directory. They always begin with a forward slash (/). Absolute paths provide a fixed way to locate files or directories, regardless of the current location in the system.

_ Relative Paths: Relative paths specify a file or directory's location in relation to the current working directory. They don't start with a slash. Relative paths offer a way to navigate the file system based on the current location.

Example:

The command pwd shows the current working directory as "/home/ryan".
The command ls Documents (using a relative path) lists files in the "Documents" directory within the current location.
The command ls /home/ryan/Documents (using an absolute path) lists files in the "Documents" directory under Ryan's home directory, regardless of the current location.
In summary, absolute paths use the root directory as a reference point, while relative paths use the current directory. Both methods can be used to specify file or directory locations, but absolute paths remain constant across different locations, while relative paths adapt to the current context.

* More About Files: 
Everything is a File: In Linux, everything, including directories, keyboards, monitors, etc., is treated as a file. This concept simplifies the understanding of how Linux manages different components.

Linux is an Extensionless System: Unlike other systems like Windows, Linux doesn't heavily rely on file extensions to determine file types. Instead, it inspects the content of a file to determine its type. This means you could have a file named "myself.png," rename it to "myself.txt," and Linux would still recognize it as an image file.

Linux is Case Sensitive: Linux distinguishes between uppercase and lowercase letters in filenames and commands. This is in contrast to systems like Windows, which are case-insensitive. Proper case usage is important for accuracy when referring to files and using commands.

Spaces in Names: Filenames and directory names can contain spaces, but spaces are also used to separate command-line arguments. To handle names with spaces, you can enclose them in quotes (single or double) or use backslashes to escape spaces. Tab completion can also help with handling spaces.

Hidden Files and Directories: Files and directories are considered hidden in Linux if their names start with a dot (.). These hidden files are typically configuration files that are not shown by default in directory listings. You can use the -a option with the ls command to display hidden files.

- Manual Pages:
 _ To access the manual pages for a specific command, you use the man command followed by the command you want to look up. For example, man ls would display the manual page for the "ls" command.

 _ Structure of Man Pages:

Line 3: Command and a brief description of its function.
Line 6: Synopsis, a quick overview of how to run the command, with optional elements enclosed in square brackets.
Line 9: Detailed description of the command.
Line 11 onwards: List of command-line options available for the command.

_Searching in Man Pages:

You can search for specific keywords in the manual pages using the man -k command followed by a search term.
Within a specific manual page, you can search by pressing forward slash ("/") followed by the search term and then hitting Enter. You can cycle through multiple occurrences using the "n" key.

_Understanding Command Line Options:

A significant aspect of working with Linux is understanding command-line options that modify command behavior.
Options often have both a long form (prefixed by two dashes, e.g., --all) and a short form (prefixed by a single dash, e.g., -a).
Long form options are more human-readable, aiding in understanding, while short form options can be more efficient when chaining multiple options together.
Short form options can be combined after a single dash, and some options require arguments.

+ File Manupulation:
_ Organizing the File System: Developing an organized directory structure is important to manage data efficiently. Avoid dumping files directly at the root of your home directory.

 _ Creating Directories with mkdir:
Use the mkdir command to create directories.
Syntax: mkdir [options] <Directory>
Examples: mkdir linuxtutorialwork, mkdir /home/ryan/foo, mkdir ~/linuxtutorialwork/dir2

_ Copying Files and Directories with cp:
Use the cp command to copy files and directories.
Syntax: cp [options] <source> <destination>
Examples: cp example1 barney, cp example2 ../../backups/example4, cp -r foo foo2

_ Moving Files and Directories with mv:
The mv command moves files and directories.
Syntax: mv [options] <source> <destination>
Examples: mv foo2 backups/foo3, mv barney backups/

_ Renaming Files and Directories:
You can use the mv command to rename files and directories by moving them within the same directory.

#this cheat sheet summarize all above commands
---
* cheat sheet summary: 
_ Basic Navigation: Explains commands like pwd, ls, and cd, along with terms like Absolute Path, Relative Path, ~ (tilde), . (dot), .. (dot dot), and TAB completion.

_ Piping and Redirection: Covers >, >>, 2>, <, and | for redirecting input and output.

_ More About Files: Introduces the file command, handling spaces in file names, and hidden files and directories.

_ Permissions: Defines permissions as read (r), write (w), and execute (x), and introduces Owner/User, Group, and Others. Covers ls -l and chmod.

_ Filters: Covers commands like head, tail, sort, wc, and grep.

_ Useful Commands: Presents commands for finding directory sizes (du -sh ./*), checking disk space (df -h), copying and renaming files (cp, mv), and finding recent files (find).

_ Shutdown and Reboot: Introduces shutdown command for system shutdown or reboot.

_ Manual Pages: Explains how to access and search through manual pages using man.

_ File Manipulation: Covers commands like mkdir, rmdir, touch, cp, mv, and rm.

_ Wildcards: Introduces wildcard characters (*, ?, []) used in file matching.

_ Process Management: Describes process management using commands like kill, ps, CTRL + C, CTRL + Z, jobs, and fg.














