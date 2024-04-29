# 🖥 Terminal Cheatsheet for Mac (Basics)

## Essential Navigation

### Navigate efficiently within the command line and files:

| Key/Command  | Description                       |
| ------------ | --------------------------------- |
| `Ctrl + A`   | Move to the beginning of the line |
| `Ctrl + E`   | Move to the end of the line       |
| `Ctrl + F`   | Move one character forward        |
| `Ctrl + B`   | Move one character back           |
| `Option + →` | Move one word forward             |
| `Option + ←` | Move one word back                |
| `Ctrl + L`   | Clear the screen                  |
| `Cmd + K`    | Clear the screen (macOS specific) |

## Core Commands

### Fundamental commands for daily file and directory management:

| Key/Command | Description                         |
| ----------- | ----------------------------------- |
| `cd`        | Change directory                    |
| `ls`        | List directory contents             |
| `pwd`       | Show current directory              |
| `mkdir`     | Create a new directory              |
| `rm`        | Remove files or directories         |
| `cp`        | Copy files or directories           |
| `mv`        | Move or rename files or directories |
| `touch`     | Create a new empty file             |

## Text Editing and Manipulation

### Manage and manipulate text directly from the command line:

| Key/Command       | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| `Ctrl + U`        | Cut from cursor to the beginning of the line                          |
| `Ctrl + K`        | Cut from cursor to the end of the line                                |
| `Ctrl + W`        | Cut the previous word                                                 |
| `Esc + Backspace` | Cut the word before the cursor, stopping at non-alphabetic characters |
| `Ctrl + Y`        | Paste the last cut text                                               |
| `Ctrl + T`        | Swap the last two characters before the cursor                        |
| `Esc + T`         | Swap the last two words before the cursor                             |

## Advanced Command Manipulation

### Chaining, redirection, and more advanced functionalities:

| Key/Command                  | Description                                              |
| ---------------------------- | -------------------------------------------------------- |
| `[command-a]; [command-b]`   | Run command A and then B, regardless of A's success      |
| `[command-a] && [command-b]` | Run B if A succeeded                                     |
| `[command-a] \| [command-b]` | Pipe output of A to B for further processing             |
| `>`, `>>`                    | Redirect command output to a file (overwrite and append) |

## Process Management

### Control and manage processes:

| Key/Command | Description                            |
| ----------- | -------------------------------------- |
| `Ctrl + C`  | Terminate the current application      |
| `Ctrl + Z`  | Suspend/stop the current application   |
| `Ctrl + D`  | Exit the current shell                 |
| `top`       | Display and manage active processes    |
| `ps`        | Report a snapshot of current processes |
| `kill`      | Send a signal to a process             |

## Searching Files

### Locate files and text within files quickly:

| Key/Command | Description                                     |
| ----------- | ----------------------------------------------- |
| `find`      | Search for files and directories                |
| `grep`      | Search inside files                             |
| `mdfind`    | Use Spotlight search for files (macOS specific) |

## Help and Information

### Access manuals and command help:

| Key/Command                | Description                                   |
| -------------------------- | --------------------------------------------- |
| `man [command]`            | Display the manual for a command              |
| `info [command]`           | Display detailed information about a command  |
| `apropos [search-pattern]` | Search the manual page names and descriptions |
