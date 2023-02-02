# Loops, conditions and parsing

# Background Context

# Resources
1. [Loops sample](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_09_01.html)
2. [Variable assignment and arithmetic](https://tldp.org/LDP/abs/html/ops.html)
3. [Comparison operators](https://tldp.org/LDP/abs/html/comparison-ops.html)
4. [File test operators](https://tldp.org/LDP/abs/html/fto.html)
5. [Make your scripts portable](https://www.cyberciti.biz/tips/finding-bash-perl-python-portably-using-env.html)

# Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg), **without the help of Google:**

## General
* How to create SSH keys
* What is the advantage of using `#!/usr/bin/env bash` over `#!/bin/bash`
* How to use `while`, `until` and `for` loops
* How to use `if`, `else`, `elif` and `case` condition statements
* How to use the `cut` command
* What are files and other comparison operators, and how to use them

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
## Shellcheck

[Shellcheck](https://github.com/koalaman/shellcheck) is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. `Shellcheck` is your friend! **All your Bash scripts must pass** `Shellcheck` **without any error or you will not get any points on the task.**

`Shellcheck` is available on the school’s computers. If you want to use it on your own computer, here is how to [install it](https://github.com/koalaman/shellcheck#installing).
Examples:

Not passing `Shellcheck`:



# Tasks
Tasks table

| Task Name  | File Name | Description |
| --------------- | ------------------------------ |---------------------------------------------------------------|
| 0. Create a SSH RSA key pair | `0-RSA_public_key.pub` | Add: RSA key pair |
| 1. For Best School loop | `1-for_best_school` | Display `Best School` 10 times |
| 2. While Best School loop | `2-while_best_school` | Display `Best School` 10 times using `while` loop |
| 3. Until Best School loop | `3-until_best_school` | Display `Best School` 10 times using `until` loop |
| 4. If 9, say Hi! | `4-if_9_say_hi` | Display `Best School` 10 times, but for the 9th iteration |
| 5. 4 bad luck, 8 is your chance | `5-4_bad_luck_8_is_your_chance` | Loop from 1 to 10 |
| 6. Superstitious numbers | `6-superstitious_numbers` | Display numbers from 1 to 20 and |
| 7. Clock | `7-clock` | Display the time for 12 hours and 59 minutes |
| 8. For ls | `8-for_ls` | Display the content of the current directory |
| 9. To file, or not to file | `9-to_file_or_not_to_file` | Give information about the `school` file |
| 10. FizzBuzz | `10-fizzbuzz` | Display numbers from 1 to 100 |
| 11. Read and cut | `100-read_and_cut` | Display the content of the file `/etc/passwd` |
| 12. Tell the story of passwd | `101-tell_the_story_of_passwd` | Display the content of the file `/etc/passwd` , using the `while` loop + IFS |
| 13. Let's parse Apache logs | `102-lets_parse_apache_logs` | Display the visitor IP along with the [HTTP status code](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes) |
| 14. Dig the data | `103-dig_the-data` | Group visitors by IP and HTTP status code, and displays this data |
