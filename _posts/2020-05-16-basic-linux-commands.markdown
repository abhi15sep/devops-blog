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
$ rm file1.txt
$ rm -rf my-folder
```

3. scp - scp command enables you to securely copy files between hosts on a network
```bash
scp ~/abhay.txt root@192.168.49.11:/usr/home/abhay.txt
```

4. shutdown - shutdown command schedules a time for the system to be powered down. It may be used to halt, power-off or reboot the machine.
```bash
$ shutdown --poweroff
```

5. sort - sort command is used to sort lines of text in the specified file(s) or from stdin.
```bash
$ sort sample.txt
```

6. ssh - ssh client is an application for remotely accessing and running commands on a remote machine. It is designed to offer a secure encrypted communications between two untrusted hosts over an insecure network such as the Internet.
```bash
$ ssh ec2-user@192.168.49.11
```

7. su - su command is used to switch to another user ID or become root during a login session. Note that when su is invoked without a username, it defaults to becoming root.
```bash
$ su 
$ su abhay
```

8. sudo - sudo command allows a permitted system user to run a command as root or another user, as defined by the security policy such as sudoers.
```bash
$ sudo apt update
$ sudo useradd abhay
$ sudo passwd abhay
```

9. sum - sum command is used to show the checksum and block counts for each each specified file on the command line.
```bash
sum output file1.txt 
```

10. tail - tail command is used to display the last lines (10 lines by default) of each file to standard output.
```bash
$ tail log-file
OR
$ tail -n 100 log-file
OR
$ tail -100f log-file  (to see floating logs)
```

11. tar - tar command is a most powerful utility for archiving files in Linux.
```bash
$ tar -cvf home.tar.gz .
tar -xvf basic.tar.gz
```

12. tee - tee command is used to read from standard input and prints to standard output and files.
```bash
$ echo "Hi how are you" | tee file.txt 
```

13. tree - The tree command is a tiny, cross-platform command-line program used to recursively list or display the content of a directory in a tree-like format.
```bash
$ tree
```

14. time - time command runs programs and summarizes system resource usage.
```bash
$ time wc /etc/passwd
```

15. top - top program displays all processes on a Linux system in regards to memory and CPU usage and provides a dynamic real-time view of a running system.
```bash
$ top
```

16. touch - touch command changes file timestamps, it can also be used to create a file as follows.
```bash
$ touch file.txt
```

17. uname - uname command displays system information such as operating system, network node hostname kernel name, version and release etc.
    Use the -a option to show all the system information:
```bash
$ uname
```

18. uptime - uptime command shows how long the system has been running, number of logged on users and the system load averages.
```bash
$ uptime
```

19. users - users command shows the user names of users currently logged in to the current host like this.
```bash
$ users
```

20. sleep - sleep command is used to delay or pause (specifically execution of a command) for a specified amount of time.
```bash
$ echo hello; sleep 5; echo bye
```