# Bash Commands

## List: ls

| `ls`             | Lists files and directories in the current folder              | ---- |
| ---------------- | ---------------------------------------------------------------| ---- |
| `ls -l`          | Shows detailed information (permissions, size, date)           | ---- |
| `ls -a`          | Includes hidden files                                           | ---- |
| `ls -lh`         | Human-readable sizes                                            | ---- |

## Navigate: cd

| `cd [foldername]` | Changes the current directory to `[foldername]`               | `cd folder` `cd \folder\name` `cd "c/folder1/folder2"` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `cd ..`          | Moves up one directory                                         | ---- |
| `cd ~`           | Goes to the home directory                                      | ---- |

## Open: start / start .

| `start [filename]` | Opens a file with the default program (Windows)               | `start file.txt` `start "document.docx"` `start image.png` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `start .`        | Opens the current directory in File Explorer (Windows)         | ---- |

## View: cat

| `cat [filename]` | Displays the content of `[filename]`                             | `cat file.txt` `cat "my file.txt"` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `cat [file1] [file2]` | Displays the content of multiple files in order           | `cat file1.txt file2.txt` `cat "file 1.txt" "file 2.txt"` |

## Create: touch

| `touch [filename]` | Creates a new empty file called `[filename]` or updates its timestamp | `touch newfile.txt` `touch "my file.txt"` |
| ---------------- | --------------------------------------------------------------- | ---- |

## Edit: nano

| `nano [filename]` | Opens `[filename]` in the nano text editor                      | `nano notes.txt` `nano "my notes.txt"` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `Ctrl+O`         | Save file                                                        | ---- |
| `Ctrl+X`         | Exit nano                                                        | ---- |

## Make directory: mkdir

| `mkdir [foldername]` | Creates a new folder called `[foldername]`                   | `mkdir myfolder` `mkdir "new folder"` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `mkdir -p [path/to/folder]` | Creates nested directories, creating parent folders if they don’t exist | `mkdir -p folder1/folder2/folder3` |

## Move/Rename: mv

| `mv [source] [dest]` | Moves or renames `[source]` to `[dest]`                     | `mv file1.txt file2.txt` `mv "my file.txt" folder/` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `mv -i [source] [dest]` | Interactive: asks before overwriting files               | `mv -i file1.txt folder/` |

## Remove: rm

| `rm [filename]`  | Deletes `[filename]`                                            | `rm file.txt` `rm "my file.txt"` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `rm -r [foldername]` | Recursively deletes a folder and its contents               | `rm -r folder1` `rm -r "my folder"` |
| `rm -i [filename]` | Interactive: asks before deleting                              | `rm -i file.txt` |

## Manual/Help: man / --help

| `[command] --help` | Shows a brief help message with options for `[command]`        | `ls --help` `cp --help` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `man [command]`  | Shows the manual page for `[command]`                            | `man ls` `man cp` |

## Copy: cp

| `cp [source] [dest]` | Copies the file `[source]` to `[dest]`                       | `cp file1.txt file2.txt` `cp "my file.txt" folder/` |
| ---------------- | --------------------------------------------------------------- | ---- |
| `cp -i [source] [dest]` | Interactive: asks before overwriting files                | `cp -i file1.txt folder/` |
| `cp -r [folder1] [folder2]` | Recursively copies a folder and its contents           | `cp -r folder1 folder2` |

## Chaining Commands

| `[command1] ; [command2]` | Runs `[command1]` then `[command2]`, regardless of success | `mkdir test ; cd test` `echo Hello ; ls` |
| ------------------------- | ----------------------------------------------------------- | ---- |
| `[command1] && [command2]` | Runs `[command2]` only if `[command1]` succeeds             | `mkdir test && cd test` `touch file.txt && cat file.txt` |




## Aliases
#### To create an aliase
- Navigate to your home directory:
```bash 
cd ~
```
- Edit (or create) the .bash_profile file:
```bash
nano .bash_profile
```
- Add the desired alias entry:
```bash
alias desktop="cd /c/Users/samar/Desktop && start ."
```
- Save press: `control + x`
- Agree press: `Y`
- Name the file, press: ` Enter ` or set the name

Once completed, you can simply type "desktop" in any new terminal session to open your Desktop folder instantly.








