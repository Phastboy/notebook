# Shell Navigations

## Overview

In this lesson, we will explore the fundamentals of navigating and examining directories in Linux.

**key commands:**

- `pwd`: print working directory.
- `cd`: change directory.
- `ls`: list directory content.

## Filesystem Hierarchical Standard (FHS)

The Filesystem Hierarchical Standard (FHS) establishes the directory structure in Linux. A quick overview is provided below:

- `/`: The root directory where the filesystem begins.
- `/home`: User home directories.
- `/root`: Home directory for root user.
- `/bin`: Essential command binaries. 
- `/boot`: static files of the boot loader.
- `/etc`: Host-specific system configuration.
- `/lib`: Essential shared libraries and kernel modules.
- `/media`: mount point for removable media. 
- `/mnt`: Mount point for mounting a filesystem temporarily.
- `/opt`: add-on application software packages.
- `/run`: Data relevant to running process.
- `/sbin`: Essential system binaries.
- `/srv`: Data for services provided by the system.
- `/tmp`: Temporary files.
- `/usr`: secondary binaries.
- `/var`: variable data.

You can visit [FHS](https://refspecs.linuxfoundation.org/fhs.shtml) to know more.


## Commands in Detail

### pwd

The `pwd` command reveals the current location within the Linux file system. It displays the working directory.

**Example:**

```
$ pwd
/home/user
```

### ls

To obtain a listing of files and directories in the current working directory, use the `ls` command.

**Example:**

```
$ ls
file1.txt file2.txt directory1 directory2
```

### cd

The `cd` command facilitates changing the working directory. If used without specifying a path, it will take you to the home directory.

**Example:**

```
$ cd /path/to/directory
```

## Path Specifications

### Absolute path

An absolute path originates from the root directory, navigating through the directory tree to reach the desired file or directory. For instance:

```
/
|-usr
|   |-bin
|   |-local
|      |-bin
|      |-etc
|      |-src
|   |-share
|-var
```
Assuming you're moving to `local/bin`, from the root, your path will be `/usr/local/bin`. That means you need to run `cd /usr/local/bin` to get to your desired directory.

### Relative path

Contrastingly, a relative path starts from the current working directory. The dot (`.`) signifies the current working directory, while dot dot (`..`) refers to the parent directory.

**Example:**

Let's move to `/usr/local/bin`, then run `cd ..`, after running the command, you should be in `/usr/local`, run `pwd` to confirm whether you're there or not.

```
$ cd /usr/local/bin
$ cd ..
$ pwd
/usr/local
```

## Useful Shortcuts

- running `cd` with no argument will take you to the home directory.
- running `cd -` will take you to the previous directory.

## Command Usage Pattern

The general pattern for command usage is:

```
command arguments
```
Here, `command` is the name of the command, and `arguments` are additional information passed to the command.

***You can use multiple arguments for a single command***.

### Arguments

Arguments in command-line usage can include various types of information depending on the specific command or script you're running. Here are common types of arguments:

1. File Paths or Directories:
    - Example: /path/to/file or /directory/

2. Options or Flags:
    - Single-character options (e.g., `-a` for "all").
    - Full-word options (e.g., `--verbose`).

3. Values or Parameters:
    - Information required by a command for a specific operation.
    - Example: `cp sourcefile destination`, `mv sourcefile destination` ...

4. Patterns:
    - Patterns or expressions used for matching files or data.
    - Example: `grep pattern filename`

And so on.

The specific types of arguments a command accepts are defined by the command itself. To understand what arguments are supported and how they should be used, you can refer to the command's manual pages using the `man` command. For example, `man ls` provides information about the ls command and its available options and arguments.

## Leveraging Command Options

Most commands come with manual pages (man pages) providing comprehensive guidance. To access a command's man page, run the following command:

```
man command
```

For example, exploring the `ls` command with `man ls` reveals all available options. Using `ls -a` showcases hidden files whose names begin with a dot (`.`). If not in the desired directory, you can specify the path as an argument, e.g., `ls -a /usr`.

***The utilization of man pages is invaluable for unlocking the full potential of a command***.
