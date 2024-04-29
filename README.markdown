# 🖥 Terminal Cheatsheet for Mac (Basics)

## Navigation

### Jump around efficiently within the command line:

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

## Editing

### Cut, copy, and manipulate text quickly:

| Key/Command       | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| `Ctrl + U`        | Cut from cursor to the beginning of the line                          |
| `Ctrl + K`        | Cut from cursor to the end of the line                                |
| `Ctrl + W`        | Cut the previous word                                                 |
| `Esc + Backspace` | Cut the word before the cursor, stopping at non-alphabetic characters |
| `Ctrl + Y`        | Paste the last cut text                                               |
| `Ctrl + T`        | Swap the last two characters before the cursor                        |
| `Esc + T`         | Swap the last two words before the cursor                             |

## Process Control

### Manage running processes easily:

| Key/Command | Description                          |
| ----------- | ------------------------------------ |
| `Ctrl + C`  | Terminate the current application    |
| `Ctrl + Z`  | Suspend/stop the current application |
| `Ctrl + D`  | Exit the current shell               |

## Basic Commands

### Core utilities and navigational commands:

| Key/Command | Description                         |
| ----------- | ----------------------------------- |
| `cd`        | Change directory                    |
| `ls`        | List directory contents             |
| `pwd`       | Show current directory              |
| `cp`        | Copy files or directories           |
| `mv`        | Move or rename files or directories |
| `rm`        | Remove files or directories         |

## Advanced Manipulations

### Chaining and combining commands:

| Key/Command                  | Description                                         |
| ---------------------------- | --------------------------------------------------- |
| `[command-a]; [command-b]`   | Run command A and then B, regardless of A's success |
| `[command-a] && [command-b]` | Run B if A succeeded                                |
| `[command-a] \| [command-b]` | Pipe output of A to B for further processing        |

## Finding Things

### Search files and text within files:

| Key/Command | Description                                     |
| ----------- | ----------------------------------------------- |
| `find`      | Search for files and directories                |
| `grep`      | Search inside files                             |
| `mdfind`    | Use Spotlight search for files (macOS specific) |

## Help and Manuals

### When you need some help:

| Key/Command                | Description                                   |
| -------------------------- | --------------------------------------------- |
| `man [command]`            | Display the manual for a command              |
| `info [command]`           | Display detailed information about a command  |
| `apropos [search-pattern]` | Search the manual page names and descriptions |
