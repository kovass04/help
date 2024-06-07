### Command Line Navigation

Let's start by looking at the basic commands used for navigation on the command line (we will discuss these in more detail below):

#### Navigation Commands

| Command              | Description                                |
|----------------------|--------------------------------------------|
| `pwd`                | Print the current directory path           |
| `clear`              | Clear the terminal window                  |
| `ls path/to/folder`  | Display the contents of a folder           |
| `ls -l path`         | Display the contents in list form          |
| `ls -a path`         | Show hidden contents                       |
| `ls -t path`         | Sort contents by date                      |
| `cd path/to/folder`  | Change the current directory               |

### Managing Files and Directories

| Command                                      | Description                                          |
|----------------------------------------------|------------------------------------------------------|
| `touch file.name`                            | Create an empty file                                 |
| `cat file.name`                              | Display the content of a file                        |
| `cat > file.name`                            | Create a file and enter the content line by line     |
| `mkdir dirname`                              | Create a new directory                               |
| `mkdir -p dir1/dir2/dir3`                    | Create directories recursively                       |
| `mv path/to/name path/to/existing-folder`    | Move a file or folder to another directory           |
| `mv path/to/name path/to/non-existing-name`  | Rename a file or folder                              |
| `cp path/to/file path/to/new-file-name`      | Copy a file                                          |
| `cp -r path/to/folder path/to/new-folder-name`| Copy a directory                                     |
| `rm path/to/file`                            | Delete a file                                        |
| `rm -r path/to/folder`                       | Delete a folder along with all its contents          |
| `rm -r path/*`                               | Delete everything inside a given folder              |
| `rm -rf path/to/folder`                      | Delete a folder without requesting additional confirmations |

### Cheat Sheet of Useful Terminal Commands

#### Basic Commands

| Command               | Description                                           |
|-----------------------|-------------------------------------------------------|
| `clear`               | Clear the terminal window                             |
| `man some-command`    | Show documentation for a given command in MacOS       |
| `some-command --help` | Show documentation for a given command in Windows     |
| `which some-command`  | Find the location of a command                        |
| `echo 'Some message'` | Display some text                                     |
| `echo $PATH`          | Display the environment variable PATH                 |

#### Files and Folders

| Command                                      | Description                                          |
|----------------------------------------------|------------------------------------------------------|
| `pwd`                                        | Print the current directory path                     |
| `ls path/to/folder`                          | Display the contents of a folder                     |
| `ls -l path`                                 | Display the contents in list form                    |
| `ls -a path`                                 | Show hidden contents                                 |
| `ls -t path`                                 | Sort contents by date                                |
| `cd path/to/folder`                          | Change the current directory                         |
| `touch file.name`                            | Create an empty file                                 |
| `cat file.name`                              | Display the content of a file                        |
| `cat > file.name`                            | Create a file and enter the content line by line     |
| `mkdir dirname`                              | Create a new directory                               |
| `mkdir -p dir1/dir2/dir3`                    | Create directories recursively                       |
| `mv path/to/name path/to/existing-folder`    | Move a file or folder to another directory           |
| `mv path/to/name path/to/non-existing-name`  | Rename a file or folder                              |
| `cp path/to/file path/to/new-file-name`      | Copy a file                                          |
| `cp -r path/to/folder path/to/new-folder-name`| Copy a directory                                     |
| `rm path/to/file`                            | Delete a file                                        |
| `rm -r path/to/folder`                       | Delete a folder along with all its contents          |
| `rm -r path/*`                               | Delete everything inside a given folder              |
| `rm -rf path/to/folder`                      | Delete a folder without requesting additional confirmations |
| `head -n 5 fileName`                         | Show the first 5 lines of a file                     |
| `tail -f file`                               | Show the last 10 lines of a file and wait for updates|
| `grep pattern file`                          | Find all matches of a pattern in a file              |
| `less path/to/file`                          | Open a file in Less (Command line text viewer)       |
| `nano path/to/file`                          | Open a file in Nano (Command line text editor)       |
| `code path/to/file`                          | Open a file in VSCode                                |

### Command History

| Command          | Description                                                     |
|------------------|-----------------------------------------------------------------|
| `Arrow UP`       | Show the previous command                                       |
| `Arrow DOWN`     | Show the next command                                           |
| `history`        | Show command history                                            |
| `history -c`     | Clear command history                                           |
| `!!`             | Execute the last command from the history                       |
| `!12`            | Execute the 12th command from the history                       |
| `!some-text`     | Execute the last command from the history that starts with the given text |
| `CTRL + R`       | Search in command history                                       |
