---
title: Welcome, this is a post about the past week from 29/04/2023
subtitle: Welcome 👋 Today we will learn about programming in the UNIX command processor and advanced programming

# Summary for listings and search engines
summary: Welcome 👋 Today we will learn about programming in the UNIX command processor and advanced programming

# Link this post with a project
projects: []

# Date published
date: '2020-12-13T00:00:00Z'

# Date updated
lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin


tags:
  - Academic


categories:
  - Demo

---

```python
import libr
print('hello')
```

### The sequence of work
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
