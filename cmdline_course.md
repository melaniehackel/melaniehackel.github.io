---
layout: default
logo: /assets/img/cmd.png
---

## Introduction

In this course, we learned how to work with the command line. We started by learning basic unix commands, that we would later pipe together. We worked on some linguistic applications on the command line after studying text file operations. We learned some basic python, how to use pip and virtual environments. Finally, connecting to remote servers and git were covered. I learned a lot in this course and can really recommend it. 

### Week 1
In the first week, I learned the basics of the command line and the following commands:

| Command | What it does |
| ------- | ------------ |
| ls | list files and directories |
| cd | change directory |
| cat | view and concatenate files|
| less | display file content |
| wget | download files from the internet |
| mv | move or rename files and directories |
| rm | delete files and directories |
| cp | copy files and directories|
| nano | text editor|

*Example:* The `ls -la` command shows all files in a directory, also hidden ones.

This week really helped me get more comfortable working on the command line and quickly switching between directories.

### Week 2

In the second week, I learned about different character encodings, basic text file operations (counting, sorting, duplicate removal), the sed-command and how to pipe commands.

With this knowledge, I worked on the following linguistic tasks:
- generating a frequency list from a text file
- converting a text into sentence-per-line format
- create a list of n-grams from a text file

*Example:* To create a frequency list from a text file, we used:

```cat text.txt | tr -s '\n\r\t ' '\n' | tr -dc '[:alnum:]\n-' | sort | uniq -c | sort -nr > text.freq```

This week was definitely harder than the first week, but it was really nice to work on some linguistic applications.

### Week 3

During this week, I learned how to write scripts, use sudo and pip to install packages and work in a virtual environment in Python.

I learned a lot during this week, that I did not know before, like working in a virtual environment. There were some technical issues, but they could all get fixed.

*Example:* 

```#!/bin/bash
echo "Hello world!"
```

This is an example of a basic command in a bash script. When called it will output *Hello world!*

### Week 4

In the last week, I learned how to connect to a remote server using scp. I also worked with git using the following commands:

- git clone
- git pull
- git add
- git commit -m
- git push
- git status
- git checkout

I have worked with git before, so much of it was just repetition. But I have never connected to a server before, so that was new knowledge.

*Example:*

```bash
git add file.py
git commit -m "update python file"
git push
```

This example shows how a git workflow can look like.
### Final project

Making this website is the final project of the course. I used Jekyll to edit the page. It was good practice to use git in the workflow and it is just very nice to have my own website now :)

*Example:* 

```bash
# Heading
[some text that is clickable](link)
*italic text*
```

These examples show how to work in a markdown file. First a #-symbol is used to make a heading. To create a clickable link, the clickable text is put into [] and the link right after into (). To make text italic, one can simply put ** around the text.
