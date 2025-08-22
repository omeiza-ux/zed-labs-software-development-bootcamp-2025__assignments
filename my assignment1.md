# Shell Basics
A shell is a program that takes commands you type (CLI) and tells the operating system to execute them.
It’s like a middleman between you and the OS.

## Shell Commands

1. Navigation
- pwd → print working directory (where you are)
- ls → list files in directory
- ls -l (detailed list)
- ls -a (show hidden files)
- cd foldername → move into a folder
- cd .. → go back one directory
- cd ~ → go to home directory

2. File & Directory Management
- mkdir project → create a new folder called project
- touch file.txt → create a new empty file
- cp file1.txt file2.txt → copy file
- mv oldname.txt newname.txt → rename/move file
- rm file.txt → delete file
- rm -r foldername → delete a folder and its contents

3. Viewing Files
- cat file.txt → print contents of a file
- less file.txt → view file page by page
- head file.txt → show first 10 lines
- tail file.txt → show last 10 lines
- nano file.txt → open file in a text editor

4. System Info
- whoami → show current user
- uname -a → show system info
- date → show date and time
- clear → clear terminal screen