# Shell Process Management

Process management involves controlling and interacting with processes running on your system.

## Running Processes in the Background

- You can run processes in the background by appending an ampersand ("&") at the end of the command.

## Managing Process IDs (PIDs)

- You can capture the PID of a background process by using the `$!` variable.
- This allows you to monitor or manipulate the process later.

## Monitoring Processes

- Monitor processes using commands like `ps`, `top`, or `htop` to view information about running processes, including their PIDs, resource usage, and more.

## Killing Processes

- Terminate processes using the `kill` command by specifying the PID of the process you want to stop. Use `kill -9` to forcefully terminate.

## Background Jobs

- Put a process in the background and bring it to the foreground with the `bg` and `fg` commands.
- This is useful when dealing with jobs that were paused or suspended.

## Process Control with `wait`

- Use the `wait` command to wait for background processes to complete before continuing with the script.

## Process Signals

- Use the `kill` command to send signals to processes.
- Common signals include `SIGTERM` (terminate), `SIGHUP` (hang up), and `SIGKILL` (forcefully terminate).

## Process Prioritization

- Use the `nice` and `renice` commands to set or modify the priority of a process, affecting CPU scheduling.

