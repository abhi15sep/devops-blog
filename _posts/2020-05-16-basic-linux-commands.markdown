---
layout: post
title:  "Basic Linux Commands"
description: "20 Linux commands every sysadmin should know"
date:   2020-05-16 21:03:36 +0530
categories: linux commands
---

Linux is an operating system's kernel. Linux is a clone of UNIX. It is created by Linus Torvalds. Linux is open-source and you can change and redistribute it in your own name. There are several Linux Distributions, commonly called “distros” like Debian, Fedora, Ubuntu linux etc.


In this article, we will introduce you a list of most frequently used Linux commands with their examples for easy learning.You can find the actual description of each Linux command in their manual page which you can access like this:

```bash
$ man command-name
```

1. pwd - pwd command displays the name of current/working directory.
```bash
$ pwd
```

2. rm - rm command is used to remove files or directories.
```bash
$ rm file1
$ rm -rf my-files
```

3. scp - scp command enables you to securely copy files between hosts on a network
```bash
scp ~/abhay.txt root@192.168.49.11:/usr/home/abhay.txt
```

4. shutdown - shutdown command schedules a time for the system to be powered down. It may be used to halt, power-off or reboot the machine.
```bash
$ shutdown --poweroff
```

5. sleep - sort command is used to sort lines of text in the specified file(s) or from stdin.
```bash
$ sort tecmint.txt
```