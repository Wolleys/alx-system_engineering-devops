# Shell, I/O Redirections and Filters
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg),
**without the help of Google:**

## Shell, I/O Redirection
* What do the commands `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr` do
* How to redirect standard output to a file
* How to get standard input from a file instead of the keyboard
* How to send the output from one program to the input of another program
* How to combine commands and filters with redirections

## Special Characters
* What are special characters
* Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them

## Other Man Pages
* How to display a line of text
* How to concatenate files and print on the standard output
* How to reverse a string
* How to remove sections from each line of files
* What is the `/etc/passwd` file and what is its format
* What is the `/etc/shadow` file and what is its format

# Requirements
## General
* Allowed editors: `vi`, `vim`, `emacs`
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
* All your files should end with a new line ([why?](https://unix.stackexchange.com/questions/18743/whats-the-point-in-adding-a-new-line-to-the-end-of-a-file/18789))
* The first line of all your files should be exactly `#!/bin/bash`
* A `README.md` file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use backticks, `&&`, `||` or `;`
* All your scripts must be executable
* You are not allowed to use `sed` or `awk`

# More Info
Read your `/etc/passwd` and `/etc/shadow` files.
Note: You do not have to learn about `fmt`, `pr`, `du`, `gzip`, `tar`, `lpr`, `sed` and `awk` yet.

# Tasks
Projects table

| Task Name  | File Name | Description |
| --------------- | ------------------------------ |---------------------------------------------------------------|
| 0. Hello World  | `0-hello_world`  | Print “Hello, World” |
| 1. Confused smiley | `1-confused_smiley` | Display a confused smiley `"(Ôo)'` |
| 2. Let's display a file | `2-hellofile` | Display the content of the `/etc/passwd` file |
| 3. What about 2? | `3-twofiles` | Display the contents of `/etc/passwd` and `/etc/hosts` |
| 4. Last lines of a file | `4-lastlines` | Display the last 10 lines of `/etc/passwd` |
| 5. I'd prefer the first ones actually | `5-firstlines` | Display the first 10 lines of `/etc/passwd` |
| 6. Line #2 | `6-third_line` | Displays the third line of the file `iacta` |
| 7. It is a good file that cuts iron without making a noise | `7-file` | Create a file |
| 8. Save current state of directory | `8-cwd_state` | Write into the file `ls_cwd_content` the result of the command `ls -la` |
| 9. Duplicate last line | `9-duplicate_last_line` | Duplicate the last line of the file `iacta` |
| 10. No more javascript | `10-no_more_js` | Delete all the regular files (not the directories) |
| 11. Don't just count your directories, make your directories count | `11-directories` | Count the number of directories and sub-directories |
| 12. What’s new | `12-newest_files` | Display the 10 newest files in the current directory |
| 13. Being unique is better than being perfect | `13-unique` | Take a list of words as input and print |
| 14. It must be in that file | `14-findthatword` | Display lines containing the pattern “root” from the file `/etc/passwd` |
| 15. Count that word | `15-countthatword` | Number of lines that contain the pattern “bin” in the file `/etc/passwd` |
| 16. What's next? | `16-whatsnext` | Display lines containing |
| 17. I hate bins | `17-hidethisword` | Lines in the file `/etc/passwd` that do not contain the pattern “bin” |
| 18. Letters only please | `18-letteronly` | Display all lines of the file `/etc/ssh/sshd_config` |
| 19. A to Z | `19-AZ` | Replace all characters `A` and `c` from input to `Z` and `e` respectively |
| 20. Without C, you would live in hiago | Remove all letters `c` and `C` from input |
| 21. esreveR | `21-reverse` | Reverse an input |
| 22. DJ Cut Killer | `22-users_and_homes` | Display all users and their home directories |
| 23. Empty casks make the most noise | `100-empty_casks` | Find all empty files and directories |
| 24. A gif is worth ten thousand words | `101-gifs` | List all the files with a `.gif` extension |
| 25. Acrostic | `102-acrostic` | Decode acrostics that use the first letter of each line |
| 26. The biggest fan | `103-the_biggest_fan` | Parse web servers logs |
