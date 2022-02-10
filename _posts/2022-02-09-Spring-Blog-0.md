---
layout: post
title: "Spring Blog 0 - Windows/Linux CLI"
date: 2022-02-09 14:29:17 -700
categories: jekyll update
---

## Windows/Linux CLI

This blog will explain the differences between Linux and Windows CLI. First, a CLI (Command Line Input) is a command line program that accepts text input and uses it to perform operating system functions. Systems administrators and software developers still continue to use the CLI to perform tasks, such as configuring computing, installing software, and accessing features that are not available via the graphical user interface.

### Windows CLI
Windows has two command-line shells: the Command shell and PowerShell. The Command shell was the first shell built into Windows to automate routine tasks. The PowerShell is similar to the Command shell, but it is more powerful because it was designed to extend the capacity of the Command shell to run PowerShell commands. The Powershell commands are called cmdlets, and it is a scripting language. The Windows command and PowerShell commands are both able to run in PowerShell, but only the Windows commands can only be used in the Command shell. 

### Linux CLI
There are many Shells available for Linux, but the most popular is Bash (Bourne-Again shell). I previously made a blog that goes more in depth about [Bash](https://jcelestino-15.github.io/jekyll/update/2021/11/19/Blog-9.html).

### Windows/Linux Commands:
Here are some of the Windows and Linux commands, but there are some commands that both Windows and Linux share.

- Directory listing
  - Windows: dir
  - Linux: ls -l
- Rename a file
  - Windows: ren
  - Linux:  mv
- Copy 
  - Windows copy: 
  - Linux: cp
- Moving a file 
  - Windows: move 
  - Linux: mv
- Delete file
  - Windows: del 
  - Linux: rm
- Print contents of a file
  - Windows: type 
  - Linux: cat
- Change file permissions
  - Windows: attrib 
  - Linux: chown/chmod
- Clear screen
  - Windows: cls 
  - Linux: clear
- Search for a string in a file
  - Windows: find
  - Linux: grep
- Display the manual of the command
  - Windows: command /?
  - Linux: man command
- Create a new directory
  - Windows: md
  - Linux: mkdir
- Prints current directory location
  - Windows: chdir
  - Linux:  pwd
- Change current directory
  - Windows and Linux: cd 
- Delete a directory
  - Windows: rmdir 
  - Linux: rmdir -rf or rmdir
- Print something on the screen
  - Windows and Linux: echo
- Leave terminal window
  - Windows and Linux: exit
