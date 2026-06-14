**Linux Basic Commands**

- `cd` - Change directory
- `cat` - View file contents
- `ls` - List the contents of the current working directory
- `mkdir` - Create a directory
- `rmdir` - Remove an empty directory
- `exit` - Exit the terminal session
- `pwd` - Display the present working directory
- `whereis` - Find the location of a command's binary, source, and manual files
- `tail` - Display the last 10 lines of a file (default)
- `head` - Display the first 10 lines of a file (default)
- `touch` - Create a file or update file timestamps
- `mv` - Move or rename a file/directory
- `rm` - Remove a file
- `ps` - Display information about running processes
- `kill -9` - Killing a process
- `cp` - Copy files and directories
- `gzip` - Compress files using the GNU zip format
- `zip` - Create and manage ZIP archives
- `tar xvf mydir.tar` - Extract files from a TAR archive
- `grep` - Search for text matching a pattern in files
- `wc` - Count lines, words, and characters in a file
- `less` - View large files efficiently without loading the entire file into memory
- `date` - Display or set the system date and time
- `df` - Show available and used disk space on file systems
- `du` - Display disk usage of files and directories
- `top` - Monitor running processes, CPU usage, and memory usage in real time

**System Log File**
- `/var/log/auth.log` - Contains system authorization information, including user logins and authentication activity
- `/var/log/lastlog` - Stores recent login information for all users; view using the `lastlog` command
- `/var/log/faillog` - Records failed login attempts; view using the `faillog` command
- `/var/log/dpkg.log` - Logs package installation and removal activity performed by the `dpkg` package manager



## File Permission 

## Permission Classes

- `u` (user) - The file owner
- `g` (group) - Members of the file's group
- `o` (others) - Users who are neither the file owner nor members of the file's group

- `chmod` - Change the access permissions of files and directories


# Common Examples

- `chmod u+x script.sh` - Give the owner execute permission
- `chmod g+w file.txt` - Give the group write permission
- `chmod o-r file.txt` - Remove read permission from others
- `chmod 755 script.sh` - Owner: rwx, Group: r-x, Others: r-x
- `chmod 644 file.txt` - Owner: rw-, Group: r--, Others: r--

**VI/VIM EDITOR**

- `vi` - Screen-oriented text editor for Unix and Linux systems

### Common VI Commands

- `vi myfile` - Open or create `myfile` in the vi editor
- `:w` - Save (write) the current file
- `:x` - Save changes and exit vi
- `:wq` - Save changes and exit vi
- `:q` - Quit vi
- `:q!` - Quit vi without saving changes



# Bash Shell Scripting

## Create a Bash Script

```bash
nano examplescript.sh
```

Add the following content to the file:

```bash
#!/bin/bash

echo "BIGDATA"
echo "ENGINEER"
```

## Run the Script

Option 1:

```bash
./examplescript.sh
```

### Output

```text
BIGDATA
ENGINEER
```


















