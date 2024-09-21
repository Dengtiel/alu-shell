# Shell Scripting Basics

This directory contains scripts that perform basic shell operations. Each script is exactly two lines long and follows the general guidelines provided.

## List of Scripts

### 0-current_working_directory
- **Description**: Prints the absolute path of the current working directory.
- **Command Used**: pwd

### 1-list_contents
- **Description**: Lists all files and directories in the current directory.
- **Command Used**: ls

### 2-change_directory
- **Description**: Changes the working directory to the user's home directory.
- **Command Used**: cd ~

### 3-list_long_format
- **Description**: Lists the contents of the current directory in a long format, displaying details like permissions, owner, size, and modification date.
- **Command Used**: ls -l

### 4-list_hidden_files
- **Description**: Lists all files in the current directory, including hidden files (those starting with a dot .).
- **Command Used**: ls -a

### 5-create_directory
- **Description**: Creates a new directory named my_dir  in the current working directory.
- **Command Used**: mkdir my_dir

### 1-listit
- **Description**: Displays the contents of the current directory.
- **Command Used**:s

### 2-bring_me_home
- **Description**: Changes the working directory to the user's home directory.
- **Command Used**: cd ~

### 3-listfiles
- **Description**: Displays the contents of the current directory in long format.
- **Command Used**: ls -l

### 4-listmorefiles
- **Description**: Displays the contents of the current directory, including hidden files, in long format.
- **Command Used**: ls -la


### 5-listfilesdigitonly
- **Description**: Displays the contents of the current directory in long format, including hidden files, with numeric user and group IDs.
- **Command Used**: ls -lan

### 6-firstdirectory
- **Description**: Creates a directory named my_first_directory  in the /tmp/  directory.
- **Command Used**: mkdir /tmp/my_first_directory

### 7-movethatfile
- **Description**: Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory/`.
- **Command Used**: `mv /tmp/betty /tmp/my_first_directory/`

### 8-firstdelete
- **Description**: Deletes the file `betty` from `/tmp/my_first_directory`.
- **Command Used**: `rm /tmp/my_first_directory/betty`

### 9-firstdirdeletion
- **Description**: Deletes the directory `my_first_directory` from `/tmp/`.
- **Command Used**: `rmdir /tmp/my_first_directory`

### 10-back
- **Description**: Changes the working directory to the previous one.
- **Command Used**: `cd -`

### 11-lists
- **Description**: Lists all files, including hidden ones, in the current directory, the parent directory, and the `/boot` directory, in long format.
- **Command Used**: `ls -la . .. /boot`

### 12-file_type
- **Description**: Prints the type of the file named `iamafile` located in the `/tmp` directory.
- **Command Used**: `file /tmp/iamafile`

### 13-symbolic_link
- **Description**: Creates a symbolic link named `__ls__` that points to `/bin/ls` in the current directory.
- **Command Used**: `ln -s /bin/ls __ls__`

### 14-copy_html
- **Description**: Copies all `.html` files from the current directory to the parent directory if they are newer or don't exist in the parent directory.
- **Command Used**: `cp -u *.html ..`

### 15-lets_move
- **Description**: Moves all files beginning with an uppercase letter to the directory `/tmp/u`.
- **Command Used**: `mv [A-Z]* /tmp/u/`

### 16-clean_emacs
- **Description**: Deletes all files in the current directory that end with the character `~`.
- **Command Used**: `rm *~`


