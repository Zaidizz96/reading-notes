## Command Lines (terminal)

  The command line is a text-based interface where commands are entered by typing. It provides a prompt, and as you type commands, the feedback is in text form.

 Most commands generate output, which is displayed immediately after executing the command. After a command completes, the terminal presents a new prompt for the next command.

 Instructions for opening a terminal on different operating systems.

 ---
 ### Basic Navigation 
 ---
  The "pwd" command in Linux shows  your current location, known as the working directory.

   The "ls" command in Linux lists the contents of a directory. It can be used with various options and locations. The basic format is:

1. ls: Lists the contents of the current directory.
2. ls -l: Performs a long listing, displaying details like permissions, owner, size, and modification time.

3. ls /etc: Lists the contents of the "/etc" directory.
4. ls -l /etc: Provides a long listing of the "/etc" directory's contents.
  In a long listing:

- Absolute Paths: These paths specify a file or directory's location starting from the root directory. They always begin with a forward slash (/).

+ Relative Paths: Relative paths specify a file or directory's location in relation to the current working directory.
---
### More About Files
--- 
Everything is a File: In Linux, everything, including directories, keyboards, monitors, etc.

Linux is an Extensionless System: Unlike other systems like Windows, Linux doesn't heavily rely on file extensions to determine file types. Instead, it inspects the content of a file to determine its type.

- #### Linux is Case Sensitive:
  Linux distinguishes between uppercase and lowercase letters in filenames and commands. This is in contrast to systems like Windows, which are case-insensitive. Proper case usage is important for accuracy when referring to files and using commands.

* #### Hidden Files and Directories:
  Files and directories are considered hidden in Linux if their names start with a dot (.). You can use the -a option with the ls command to display hidden files. 

---
### File Manupulation:
---

 - #### Creating Directories with mkdir:
   Use the mkdir command to create directories.
   Syntax: mkdir [options] <Directory>.


+ #### Copying Files and Directories with cp:
  Use the cp command to copy files and directories.
  Syntax: cp [options] (source) (destination).

* #### Moving Files and Directories with mv:
  The mv command moves files and directories.
  Syntax: mv [options] (source) (destination).


- #### Renaming Files and Directories:
  You can use the mv command to rename files.
