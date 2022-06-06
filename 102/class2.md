# Class 2 Reading Notes

## Classifications of Text Editors

- software that comes with your computer (Text Edit on Mac, Notepad on Windows)
  - tend to be more barebones than other text editors
  - make sure to code in plain textand saved with the appropriate extension
- Third party options
  - includes more features than built in text editors such as syntax highlighting, themes and code completion
  - many are free but some cost money

### IDE

IDE stands for Integrated Development Environment. It is a suite of software including a text editor, a file manager, a compiler, and a debugger all in one

## Command Line

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell.

### Basic Navigation

`pwd` stands for "print working directory" and tells you what the current working directory is

`ls` is short for "list", and by itself is just a plain listing of the current location. It can be modified with options to make it more powerful

- `ls -l` is a a much more detailed listing
- `ls -l /etc` lists the directory's contents instead of the current directory itself

A path is a means to get to a particular file or directory in the system

- **Absolute paths** specify a location (file or directory) in relation to the root directory, the directory at the top of the hierachy. You can identify them easily as they always begin with a forward slash ( / )
- **Relative paths** specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

`cd` stands for "change directory", it is usually followed by a location the user is trying to change to

### About Files

Everything is a file under Linux, including directories, keyboards (read-only) and monitors (write-only)

Linux is an extensionless system, meaning it ignores a file's extension when determining what type of file it is.

You can use the `file` command to determine what a file with no extension is.

Linux, unlike other operating systems such as Windows, is case sensitive. For example, "File.txt" and "file.txt" would be read as distinct and seperate.

If a file or directory has spaces in the name, use quotes (single or double) around the term or a backslash (known as an escape character) infront of the space in order to insure the name is read as one term.

Files and directories can be hidden by beginning the name with a "."

- modify the `ls` command with `-a` to list hidden files along with the rest of the directory
