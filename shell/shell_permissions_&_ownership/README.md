# Shell permissions and ownership

These permissions determines who can access, modify or execute a file or a directory.

## Viewing permissions

1. To view permissions, we can use the `ls` command but with the `-l` option, if you've checked the manual check for `ls`, you would have already know. It displays information about the about permissions, owners, and size of a files and directories.
2. The `stat` command also provide detailed information about a file or directory.

## Types of permissions

- Read (`r`): It allows you to view the content of a file or list the content of a directory.
- Write (`w`): It allows you to modify, edit and delete a file or its content as well as creating and delete files and directory within a directory.
- Execute (`x`): Grants the permission to execute a file as a program or script.

**Numerical Representation:**
- Read (`r`): 4
- Write (`w`): 2
- Execute (`x`): 1
- No permission (`-`): 0

The sum of these numbers represents the permission set.


## Permission Levels

- Owner: The user who owns a file or a directory.
- Group: Group who share specific.
- Others: All other user who are not part of the owner or part of the group.

## Changing permissions and ownership

### Changing permissions

- You can change permissions using the `chmod` command, followed by numeric or symbolic notation.
- Symbolic notation allows for more flexibility and can be used to add or remove permissions without altering the existing ones. For example `chmod +x file.sh` adds execution permission to `file.sh`.
- In numeric notation, a number represents the permissions for a level (each level have three permissions), so, a number represent all permission for a level, and three numbers will represent all the permissions. For example `644` represent `rw-r--r--`, `510` represent `r-x--x---`.

#### Examples for Changing Permissions

1. **Symbolic Notation for Adding and Removing Permissions:**
    - Use `chmod` with symbolic notation to add (`+`) or remove (`-`) permissions.
        ```
        chmod +x file.sh # adds execute permission to file.sh.

        chmod -w file.txt # removes write permission from file.txt
        ``` 

2. **Numeric Notation for Setting Specific Permissions:**

    - Use `chmod` with numeric notation to set specific permissions.
    ```
    chmod 644 file.txt  # sets read and write for owner, read for group and others
    chmod 510 script.sh # sets read and execute for owner, execute for group, and no permissions for others
    ```


### Changing ownership
- You can use `chown` and `chgrp` commands to change owner and group of a file.

**Example**
```
chown newowner:newgroup file.txt   # changes owner and group of file.txt
```
