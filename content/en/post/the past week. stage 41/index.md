---
title: Programming in the UNIX OS command processor. Advanced programming
date: 2023-05-29
math: true
image:
  placement: 2
  caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
---

## Work purpose

Learn the basics of programming in the UNIX OS shell. Learn how to write more complex command files using logical control constructs and loops.

## The sequence of work

1. Write a batch file implementing a simplified semaphore mechanism. The command file must wait for some time t1
for the resource to be released, giving a message about it, and after waiting for its release, use
it for some time t2<>t1, also giving information that
the resource is being used by the corresponding command file (process). Run
a batch file in one virtual terminal in the background, redirecting
its output to another (> /dev/tty#, where # is the number of the terminal to which it is redirected
output), in which this file is also running, but not in the background, but in privileged
mode. Modify the program so that there is a possibility of interaction of three
or more processes.
2. Implement the man command using a batch file. Examine the contents of the kata log /usr/share/man/man1. It contains archives of text files containing
help for most of the programs and commands installed in the system. Each archive
can be opened with the less command immediately after viewing the contents of the help. The command
file should receive the command name as a command line argument and as
the result is to issue a help about this command or a message about the absence of help
if the corresponding file is not in the man1 directory.
3. Using the built-in variable $RANDOM, write a command file that generates a random sequence of letters of the Latin alphabet. Note that $RANDOM
outputs pseudo-random numbers in the range from 0 to 32767.
