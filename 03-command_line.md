# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > $ pwd (show current working directory path)  
    $ cd (change directory)  
    $ cd .. (move up one directory)  
    $ ls (list all all files and directories in the working directory.)  
    $ mkdir 'filename' (creating a directory)  
    $ touch 'filename'.'filetype' (creating a file using `touch` command)  
    $ ls -a (listing hidden files / files starting with a dot '.')  
    $ cp 'filename' (copying a file from one directory to another)  
    $ rm -r 'directory name' or rmdir 'directory name' (deleting a directory)  
    $ rm 'filename'.'filetype' (deleting a file)  
    $ mv 'old filename' 'new filename' (renaming a file)  
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > $ ls (list all all files and directories in the working directory)  
    $ ls -a (lists hidden files / files starting with a dot '.')  
    $ ls -l (lists files and directories as a table)  
    $ ls -t (orders files and directories by the time they were last modified)  
    $ ls -lh (lists files and directories as a table and shows sizes in human readable format)  
    $ ls -lah (lists files and directories as a table, shows sizes in human readable format and listing hidden files)  
    $ ls -Glp (lists files and directories as a table, uses different colors to show different file type and adds '/' if the 
    file type is FOLDER)  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > $ ls -1 (shows single entry per line)  
    $ ls -ld (shows only the details of directory instead of all files)  
    $ ls -lt (orders files based on last modified time)
    $ ls -ltr (orders files based on last modified time - In Reverse Order) 
    $ ls -F (classifies the file with different special character for different kind of files)

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > The xargs command is a command line utility for building an execution pipeline from standard input. For example, if we want to create three folders named 'a', 'b', 'c', we can use xargs command to do so and the code is as follows.
 

