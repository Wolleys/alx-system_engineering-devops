# Shell, init Files, Variables and Expansions
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg),
**without the help of Google:**

## General
* What happens when you type `$ ls -l *.txt`

## Shell Initialization Files
* What are the `/etc/profile` file and the `/etc/profile.d` directory
* What is the `~/.bashrc` file

## Variables
* What is the difference between a local and a global variable
* What is a reserved variable
* How to create, update and delete shell variables
* What are the roles of the following reserved variables: HOME, PATH, PS1
* What are special parameters
* What is the special parameter `$?`?

## Expansions
* What is expansion and how to use them
* What is the difference between single and double quotes and how to use them properly
* How to do command substitution with `$()` and backticks

## Shell Arithmetic
* How to perform arithmetic operations with the shell

## The `alias` Command
* How to create an alias
* How to list aliases
* How to temporarily disable an alias

## Other `help` pages
* How to execute commands from a file in the current shell

# Requirements
## General
* Allowed editors: `vi`, `vim`, `emacs`
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
* All your files should end with a new line ([why?](https://unix.stackexchange.com/questions/18743/whats-the-point-in-adding-a-new-line-to-the-end-of-a-file/18789))
* The first line of all your files should be exactly `#!/bin/bash`
* A `README.md` file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use `&&`, `||` or `;`
* You are not allowed to use `bc`, `sed` or `awk`
* All your scripts must be executable

# More Info
* Read your `/etc/profile`, `/etc/inputrc` and `~/.bashrc` files.
* Look at some files in the /etc/profile.d directory.
* Note: You do not have to learn about `awk`, `tar`, `bzip2`, `date`, `scp`, `ulimit`, `umask`, or shell scripting, yet.

# Tasks
Projects table

| Task Name  | File Name | Description |
| --------------- | ------------------------------ |---------------------------------------------------------------|
| 0. `<o>`  | `0-alias`  | Create an alias |
