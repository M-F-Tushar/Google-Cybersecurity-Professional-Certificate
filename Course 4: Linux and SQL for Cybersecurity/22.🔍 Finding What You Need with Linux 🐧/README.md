# 🔍 Finding What You Need with Linux 🐧

## Introduction
Now that we've covered `pwd`, `ls`, and `cd` and are familiar with these basic commands for navigating the Linux file system, let's explore a couple of ways to find what you need within this system. 🌟

## Filtering Information 📋
As a security analyst, your work will likely involve filtering for the information you need. Filtering means searching your system for specific information that can help you solve complex problems. For example, imagine your team determines a piece of malware contains a string of characters. You might be tasked with finding other files with the same string to determine if those files contain the same malware. Later, we'll learn more about how you can use SQL to filter a database, but Linux is a good place to start basic filtering. 🔐

### Using `grep` Command 🔎
The `grep` command searches a specified file and returns all lines in the file containing a specified string. Here's an example:
- Imagine we have a file called `updates.txt`, and we're currently looking for lines that contain the word "OS." If the file is large, it would take a long time to visually scan for this. Instead, after navigating to the directory that contains `updates.txt`, we'll type the command: `grep OS updates.txt` into the shell.
  - The `grep` command is followed by two arguments. The first argument is the string we're searching for; in this case, "OS." The second argument is the name of the file we're searching through, `updates.txt`. When we press enter, Bash returns all lines containing the word "OS."

### Introducing Piping 🚰
Piping is a Linux command that can be used for various purposes. The piping command sends the standard output of one command as standard input into another command for further processing. It's represented by the vertical bar character `|`. 🔄

### Using Piping with `grep` 🌐
The `grep` command can also be incorporated after a pipe. Here's an example:
- The first command, `ls`, instructs the operating system to output the file and directory contents of the `reports` subdirectory. But because the command is followed by the pipe, the output isn't returned to the screen. Instead, it's sent to the next command. The `grep` command then searches for a specified string of characters; in this case, it's "users." 
  - Let's use this in Bash. First, we output everything in the `reports` directory. If we were already in the directory, we would just need to input `ls`. But since we're not, we'll specify the path to this directory. When we press enter, the output indicates there are seven files in the `reports` directory. To return only the files that contain the word "users," we'll combine the `ls` command with piping and the `grep` command. As the output demonstrates, Linux has been instructed to return only files that contain the word "users." The two files that don't contain this string no longer appear.

## Conclusion 🌟
Now you have two different ways to filter in Linux while working as an analyst. Navigating through files and filtering are just part of what you need to know. Let's keep exploring the Linux command line.

