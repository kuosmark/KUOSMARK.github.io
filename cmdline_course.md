---
layout: default
---

## Command-Line Course
The course is an introduction to the UNIX environment and the Bash command line. It's taught from a linguistic's perspective but is useful for everyone. As a second-year computer science student, I already knew a lot of the course matter, but I still learned new things and formed a better understanding of others.

### Introduction to Command-Line Environments
Bash is the most used UNIX command language. It's run by the Bash interpreter in a terminal, or shell. Cp for copying and mv for moving and renaming files are commonly used Bash commands. Nano and Vim are popular command line text editors.

`mv directory1/file1 directory2/` moves file1 to directory2.

I knew most of the first week's subject matter. I learned some details about file extensions and how Unix and Linux are different from each other.

### Navigating a UNIX System
Unix systems have different user roles. The superuser account has the privilege to make unrestricted system-wide changes. Sudo is used to run programs as the superuser. The chmod command is used to change file permissions. Ssh is a secure connection over which it is possible to contact a remote server.

`sudo su` changes the current user to superuser.

I knew most of the second week's topic beforehand, but the part about processes in Unix I wasn't too familiar with.

### Corpus Processing
The command line can be a useful tool for linguists. Pipes are used to redirect the output of a program as the input of another one. Grep matches plain-text data to a regular expression.

`cat book.txt | grep "word" | wc -l` prints the number of lines in book.txt where "word" is found.

I learned a lot this week. I hadn't done very much piping and text processing through the command line before. Some commands like sed were completely new to me.

### Scripting and UNIX Configuration Files
The .bashrc file is used for bash command line configuration. Shell scripts are programs for automating command line tasks.

`./script.sh file1 file2` runs the shell script with input file1 and output file2.

This was clearly the most difficult week of the course. Nearly everything about scripting was new to me. Due to a lack of time, I wasn't able to complete all of the week's exercises. This has to be my weak spot in this courses subject matter.

### Installing and Running Programs
* APT (Advanced Package Tool) and Homebrew are package management systems that handle the installation and removal of software.
* Python modules can be installed using pip.
* Make is used for building programs, libraries and projects.

<img src="assets/images/python.png" alt="The Python logo" hspace="20" width="50%" align="right"/> 

`sudo apt-get upgrade` fetches new versions of existing packages

I learned about the running and installation of C programs and using make. I had already used Python for some of my own projects.

### Version Control
Git is a widely-used version control system. It helps to manage software development and keeps track of the entire history of projects. Git helps people to collaborate on projects and easily merge different features together. Github is a hosting service for git repositories and also a social network for developers.

| Command | Description | Example |
| --- | --- | --- |
| clone | downloads a project and its entire version history | $ git clone [url] |
| commit | records staged file snapshots in version history | $ git commit -m"[commit message]" |
| push | uploads all local commits to GitHub | $ git push |
| log | lists version history for the current branch| $ git log |

This was probably the easiest week for me. I've used git for the entirety of my studies. The topic was very familiar and there wasn't that much new information for me.

### Building Webpages using GitHub Pages
Github pages is a service for hosting static web pages directly from a GitHub repository. Jekyll is a tool for generating static sites locally. Markdown is a lightweight markup language commonly used for software project documentation.

`*This is markdown code inside a markdown file.*` Asterisks are used to emphasize the text.

I'm used to making homepages and such, but haven't made a page with GitHub Pages before. The final assignment hasn't been all that difficult, quite the contrary. Allthough, I'm writing this on the night before Christmas Eve so my time planning haven't been all that successful.
