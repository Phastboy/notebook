# Shell Redirections and Piping

Shell redirection and piping are crucial for manipulating data flow in a Unix-like shell environment.

## I/O Redirection

- `>`: Redirects the standard output of a command to a file. For example, `ls > file.txt` will save the list of files and directories in the current working directory to `file.txt`.
- `>>`: Appends the standard output of a command to a file.
- `<`: Takes input from a file rather than the keyboard.
- `2>` (Error Output Redirection): Redirects error messages (standard error) to a file.
- `&>` (Combined Output Redirection): Redirects both standard output and error to a file.
- `tee`: Used for redirecting output to both a file and standard output simultaneously.

### Practical Examples for I/O Redirection

1. Redirecting standard output and error to a file:
   ```bash
   command &> output.log
    ```
2. Using `tee` to save output to a file and display on the terminal:
    ```bash
    command | tee output.txt
    ```
## piping 

Piping allows you to send the output of one command as the input to another command.

You can chain multiple commands to perform complex data processing.

- `|` is used for piping.

- `<<` (here documents): 
		○ Allows you to provide input to a command within a script or a terminal session.
- `<()` & `>()` (process substitution): it helps you treat the output of a command as a file.

## Examples

### Complex Piping Scenario

Chaining multiple commands for complex data processing:

``` bash
command1 | command2 | command3
```

### Use Case for Here Documents

Providing input to a command within a script:

```bash
cat << END
This is the content
of the here document.
END
```

### Process substitution

Using process substitution to treat command output as a file:

```bash
diff <(command1) <(command2)
```

***It's essential to handle errors appropriately when using redirection and piping to ensure effective command execution.***
