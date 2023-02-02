# Processes and signals

# Resources
1. [Linux PID](http://www.linfo.org/pid.html)
2. [Linux process](https://www.thegeekstuff.com/2012/03/linux-processes-environment/)
3. [Linux signal](https://www.educative.io/answers/what-are-linux-signals)
4. [Process management in linux](https://www.digitalocean.com/community/tutorials/process-management-in-linux)

# Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg), **without the help of Google:**

## General
* What is a PID
* What is a process
* How to find a process’ PID
* How to kill a process
* What is a signal
* What are the 2 signals that cannot be ignored

# Requirements
## General
* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be interpreted on `Ubuntu 20.04 LTS`
* All your files should end with a new line
* A `README.md` file, at the root of the folder of the project, is mandatory
* All your Bash script files must be executable
* You are not allowed to use `awk`
* Your Bash script must pass `Shellcheck` (version `0.7.0`) without any error
* The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
* The second line of all your Bash scripts should be a comment explaining what is the script doing

# More Info
For those who want to know more and learn about all signals, check out [this article](https://www.computerhope.com/unix/signals.htm).

# Tasks
Tasks table

| Task Name  | File Name | Description |
| --------------- | ------------------------------ |---------------------------------------------------------------|
| 0. What is my PID | `0-what-is-my-pid` | Display own PID |
| 1. List your processes | `1-list_your_processes` | Display a list of currently running processes |
| 2. Show your Bash PID | `2-show_your_bash_pid` | Display lines containing the `bash` word |
| 3. Show your Bash PID made easy | `3-show_your_bash_pid_made_easy` | Display the PID, along with the process name |
| 4. To infinity and beyond | `4-to_infinity_and_beyond` | Display To infinity and beyond indefinitely |
| 5. Don't stop me now! | `5-dont_stop_me_now` | Stop `4-to_infinity_and_beyond` process |
| 6. Stop me if you can | `6-stop_me_if_you_can` | Stop `4-to_infinity_and_beyond` process |
| 7. Highlander | `7-highlander` | Display `To infinity and beyond` indefinitely |
| 8. Beheaded process | `8-beheaded_process` | Kill the process `7-highlander` |
| 9. Process and PID file | `100-process_and_pid_file` | Create the file `/var/run/myscript.pid` containing its PID |
| 10. Manage my process | `101-manage_my_process, manage_my_process` | A `manage_my_process` Bash script that |
| 11. Zombie | `102-zombie.c` | A C program that creates 5 zombie processes |
