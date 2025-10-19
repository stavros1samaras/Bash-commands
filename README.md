# Bash Commands

## List: ls

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `ls`             | Lists files and directories in the current folder              |
| `ls -l`          | Shows detailed information (permissions, size, date)           |
| `ls -a`          | Includes hidden files                                           |
| `ls -lh`         | Human-readable sizes                                            |

## Navigate: cd

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `cd [foldername]` | Changes the current directory to `[foldername]`               |
| `cd ..`          | Moves up one directory                                         |
| `cd ~`           | Goes to the home directory                                      |

## Open: start / start .

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `start [filename]` | Opens a file with the default program (Windows)               |
| `start .`        | Opens the current directory in File Explorer (Windows)         |

## View: cat

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `cat [filename]` | Displays the content of `[filename]`                             |
| `cat [file1] [file2]` | Displays the content of multiple files in order           |

## Create: touch

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `touch [filename]` | Creates a new empty file called `[filename]` or updates its timestamp |

## Edit: nano

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `nano [filename]` | Opens `[filename]` in the nano text editor                      |
| `Ctrl+O`         | Save file                                                        |
| `Ctrl+X`         | Exit nano                                                        |

## Make directory: mkdir

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `mkdir [foldername]` | Creates a new folder called `[foldername]`                   |
| `mkdir -p [path/to/folder]` | Creates nested directories, creating parent folders if they don’t exist |

## Move/Rename: mv

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `mv [source] [dest]` | Moves or renames `[source]` to `[dest]`                     |
| `mv -i [source] [dest]` | Interactive: asks before overwriting files               |

## Remove: rm

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `rm [filename]`  | Deletes `[filename]`                                            |
| `rm -r [foldername]` | Recursively deletes a folder and its contents               |
| `rm -i [filename]` | Interactive: asks before deleting                              |

## Manual/Help: man / --help

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `man [command]`  | Shows the manual page for `[command]`                            |
| `[command] --help` | Shows a brief help message with options for `[command]`        |

## Copy: cp

|                  |                                                                 |
| ---------------- | --------------------------------------------------------------- |
| `cp [source] [dest]` | Copies the file `[source]` to `[dest]`                       |
| `cp -i [source] [dest]` | Interactive: asks before overwriting files                |
| `cp -r [folder1] [folder2]` | Recursively copies a folder and its contents           |
| `cp -a [folder1] [folder2]` | Archives: preserves properties like permissions, timestamps, symlinks |
| `cp -v [source] [dest]` | Verbose: shows what is being copied                           |
