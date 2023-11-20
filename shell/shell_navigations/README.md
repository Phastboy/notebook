# Shell Navigations

## Overview

In this lesson, we'll learn how to move around, look into a directory.
The basic command we'd using here include:
- `pwd`: print working directory.
- `cd`: change directory.
- `ls`: list directory content.

## FHS

FHS refers to filesystem hierarchical standard. You can visit [FHS](https://refspecs.linuxfoundation.org/fhs.shtml) to know more, but i'll do a quick highlight.

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


**pwd**

Your current in the linux files is your working directory, to see the name of the directory use `pwd`.

**ls**

To list the files and directories in the working directory, use `ls` command.

**cd**

To change your working directory, use `cd` followed by the path name of the directory, because using just the `cd` command will take you to the home directory.

## Absolute path

An absolute path begins with the root directory and follows the tree branch to the desired file or directory.
Example:

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
so, let say you're moving to `local/bin`, from the root, your path will be `/usr/local/bin`. That means you need to run `cd /usr/local/bin` to get to your desired directory.

## Relative path

A relative path starts from the current working directory.dot (.) represent the current working directory and dot dot(..) represent the parent directory of the working directory.
Example:

Let's move to `/usr/local/bin`, then run `cd ..`, after running the command, you should be in `/usr/local`, run `pwd` to confirm whether you're there or not.

## Shortcuts

- running `cd` with no argument will take you to the home directory.
- running `cd -` will take you to the previous directory.

**Usage of commands**

The usage pattern of almost every command is:
```
command -options arguments
```
where _command_ is the name of the command you want to use, _-options_ is the available flags to control the behaviour of the command, and _arguments_ is one or more files or directory upon which the command operates.

Almost all commands have man pages, so if you're not sure about using a command, you can check the man page for guide.
To check a command man page, run `man command`. Replace _command_ with the command you're having issues with.

Man pages is really helpful to explore the full power of a command.

Let's take `ls` command for example:
run `man ls` and you'll see all available options for ls. let's choose the _-a_ option and see what it does. run `ls -a` and you'll notice that files and directories that their name started with dot(.) are also listed with the normal files and directories. Normally, all files and directory that their name started with dot(.). are hidden files but the _-a_ option gives us the chance to see them.

If you're not in the directory that you want see it's content, you can add the path of the directory as an argument.e.g `ls -a /usr`.
