# Shell Environment Variables

Environment variables store information that various processes and commands within the shell can access and use.

## 1. Viewing Environment Variables

- Use `env` and `printenv` to view all environment variables.

    **Example:**
    ```bash
    env
    ```

## 2. Setting Environment Variables

- Use the `export` command followed by the variable and its value to set environment variables in the shell.

    **Example:**
    ```bash
    export MY_VARIABLE="Hello, World!"
    ```

## 3. Accessing Environment Variables

- Use the variable name preceded by a dollar sign to access its value.

    **Example:**
    ```bash
    echo $MY_VARIABLE
    ```

## 4. System Environment Variables

- Operating systems or specific applications set variables that control system/application behavior or provide essential information.

## 5. Unsetting Environment Variables

- Use the `unset` command followed by the variable name to remove a variable.
- After unsetting, you can no longer access the value of the variable.

    **Example:**
    ```bash
    unset MY_VARIABLE
    ```

## 6. Default Environment Variables

- Shells like Bash come with default environment variables, including `HOME` (the user's home directory), `USER` (the user name), and `SHELL` (the path to the default user shell).

## 7. Customization and Configuration

- Environment variables are used to customize or configure the shell behavior.

    **Example:**
    ```bash
    export EDITOR="vim"
    ```

## 8. Scripting and Automation

- Environment variables are used to pass information between different parts in shell scripts.

    **Example:**
    ```bash
    # Script.sh
    # Accessing environment variable in a script
    echo "Welcome, $USER!"
    ```

