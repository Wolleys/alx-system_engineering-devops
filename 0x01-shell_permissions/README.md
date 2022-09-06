# Shell, Permisions
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg), 
**without the help of Google:**

## Permissions
* What do the commands `chmod`, `sudo`, `su`, `chown`, `chgrp` do
* Linux file permissions
* How to represent each of the three sets of permissions (owner, group, and other) as a single digit
* How to change permissions, owner and group of a file
* Why can’t a normal user `chown` a file
* How to run a command with root privileges
* How to change user ID or become superuser

## Other Man Pages
* How to create a user
* How to create a group
* How to print real and effective user and group IDs
* How to print the groups a user is in
* How to print the effective user id

# Requirements
## General
* Allowed editors: `vi`, `vim`, `emacs`
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
* All your files should end with a new line ([why?](https://unix.stackexchange.com/questions/18743/whats-the-point-in-adding-a-new-line-to-the-end-of-a-file/18789))
* The first line of all your files should be exactly `#!/bin/bash`
* A `README.md` file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use backticks, `&&`, `||` or `;`
* All your scripts must be executable.

# Tasks
Projects table

| Task Name  | Script Name | Description |
| --------------- | ------------------------------ |---------------------------------------------------------------|
| 0. My name is Betty  | `0-iam_betty`  | Switch the current user to the user betty |
| 1. Who am I | `1-who_am_i` | Print the effective username of the current user |
| 2. Groups | `2-groups` | Print all the groups the current user is part of |
| 3. New owner | `3-new_owner` | Change the owner of the file hello to the user betty |
| 4. Empty! | `4-empty` | Create an empty file called hello |
| 5. Execute | `5-execute` | Add execute permission to the owner of the file hello |
