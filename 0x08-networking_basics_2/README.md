# Networking basics 1

# Resources
1. [What is localhost](https://en.wikipedia.org/wiki/Localhost)
2. [What is 0.0.0.0](https://en.wikipedia.org/wiki/0.0.0.0)
3. [What is the hosts file](https://www.makeuseof.com/tag/modify-manage-hosts-file-linux/)
4. [Netcat examples](https://www.thegeekstuff.com/2012/04/nc-command-examples/)

# Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg), **without the help of Google:**

## General
* What is localhost/127.0.0.1
* What is 0.0.0.0
* What is `/etc/hosts`
* How to display your machine’s active network interfaces

# Requirements
## General
* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be interpreted on `Ubuntu 20.04 LTS`
* All your files should end with a new line
* A `README.md` file, at the root of the folder of the project, is mandatory
* All your Bash script files must be executable
* Your Bash script must pass `Shellcheck` (version `0.7.0` via `apt-get`) without any errors
* The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
* The second line of all your Bash scripts should be a comment explaining what is the script doing

# Tasks
Tasks table

| Task Name  | File Name | Description |
| --------------- | ------------------------------ |---------------------------------------------------------------|
| 0. Change your home IP | `0-change_your_home_IP` | Configure an Ubuntu server with the below requirements |
| 1. Show attached IPs | `1-show_attached_IPs` | Display all active IPv4 IPs on the machine |
| 2. Port listening on localhost | `100-port_listening_on_localhost` | Listen on port `98` on `localhost` |
