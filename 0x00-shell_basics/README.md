# Shell, Basics
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg), 
**without the help of Google:**

## General
* What does RTFM mean
* What is a Shebang

## What is the Shell
* What is the shell
* What is the difference between a terminal and a shell
* What is the shell prompt
* How to use the history (the basics)

## Navigation
* What do the commands or built-ins `cd`, `pwd`, `ls` do
* How to navigate the filesystem
* What are the `.` and `..` directories
* What is the working directory, how to print it and how to change it
* What is the root directory
* What is the home directory, and how to go there
* What is the difference between the root directory and the home directory of the user root
* What are the characteristics of hidden files and how to list them
* What does the command `cd -` do

## Looking Around
* What do the commands `ls`, `less`, `file` do
* How do you use options and arguments with commands
* Understand the ls long format and how to display it
* [A Guided Tour](http://linuxcommand.org/lc3_lts0040.php)
* What does the `ln` command do
* What do you find in the most common/important directories
* What is a symbolic link
* What is a hard link
* What is the difference between a hard link and a symbolic link

## Manipulating Files
* What do the commands `cp`, `mv`, `rm`, `mkdir` do
* What are wildcards and how do they work
* How to use wildcards

## Working with Commands
* What do `type`, `which`, `help`, `man` commands do
* What are the different kinds of commands
* What is an alias
* When do you use the command help instead of man

## Reading Man Pages
* How to read a man page
* What are man page sections
* What are the section numbers for User commands, System calls and Library functions

## Keyboard Shortcuts for Bash
* Common shortcuts for Bash

# Requirements
## General
* Allowed editors: `vi`, `vim`, `emacs`
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
* All your files should end with a new line ([why?](https://unix.stackexchange.com/questions/18743/whats-the-point-in-adding-a-new-line-to-the-end-of-a-file/18789))
* The first line of all your files should be exactly `#!/bin/bash`
* A `README.md` file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use backticks, `&&`, `||` or `;`
* All your scripts must be executable. To make your file executable, use the `chmod` command: `chmod u+x file`.

# Tasks

| Task Name  | Script Name | Description |
| --------------- | ------------------------------ |---------------------------------------------------------------|
| 0. Where am I?  | `0-current_working_directory`  | Print the absolute path name of the current working directory |
| 1. What’s in there?| `1-listit` | Display the contents list of your current directory |
| 2. There is no place like home | `2-bring_me_home` | Change the working directory to the user’s home directory|
| 3. The long format | `3-listfiles` | Display current directory contents in a long format |
| 4. Hidden files | `4-listmorefiles` | Display current directory contents, including hidden files using long format |
| 5. I love numbers | `5-listfilesdigitonly` | Display current directory contents |







