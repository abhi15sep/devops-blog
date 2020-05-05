---
layout: post
title:  "Fast – Internet Speed test in Linux"
description: "Small speed test binary to test your internet download speed in Linux"
date:   2020-05-04 21:03:36 +0530
categories: SpeedTest Utility
---
If you want to check the current internet speed of your Linux server from the command-line, you can use a utility called `fast` – a minimal zero-dependency script, written in `Go language` for testing your internet download speed from the terminal, which is powered by `Fast.com – Netflix` and runs on `Linux, Windows` and `Mac`.

To use, [download binary file](https://github.com/ddo/fast/releases) for your architecture (fast_linux_amd64 for 64bit systems) in your home directory, set execute permission and run it directly from the terminal to test your server Internet speed.

```bash
$ wget https://github.com/ddo/fast/releases/download/v0.0.4/fast_linux_amd64 -O fast
$ chmod +x fast
$ ./fast
```
If you want, you can install it under `/usr/local/bin directory` on any Linux distribution by using the following commands.

```bash
$ wget https://github.com/ddo/fast/releases/download/v0.0.4/fast_linux_amd64 
$ sudo install fast_linux_amd64 /usr/local/bin/fast
$ fast
```
You can also install `Fast` on any Linux distribution using `snap` (requires `snapd` to be installed on the system).

```bash
$ snap install fast
```

Enjoy!!
