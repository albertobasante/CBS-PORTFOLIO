# Linux Notes

## 1. Basic Concepts

Linux is an operating system widely used in cybersecurity, servers and network infrastructure.

## 2. Important Directories

- `/home` → User files and personal folders.
- `/etc` → System and application configuration files.
- `/var` → Logs and files that change frequently.
- `/tmp` → Temporary files.
- `/usr` → Programs and system resources.
- `/bin` → Essential system commands.

## 3. Basic Commands
 - `pwd` → Where am I
 - `ls` → What is in here, if you add -la more info and documents
 - `cd` → Move to      ..=go up a level ~=personal folder
 - `mkdir` → Create a folder
 - `touch` → Create a file
 - `cat` → Read file
 - `echo` → Edit file  echo "hello" > text.txt overwrites ">>" adds at the end
 - `cp` → copy cp (file to copy) (new file) 
 - `mv` → move or rename
 - `rm` → delete
 - `grep` → search text (useful to find info in logs, config, etc)
 - `find` → search file find (where to start) (-name/iname) (text.txt/*.txt*)
 - `chmod` → change permits chmod (number) (file)
 - `sudo` → commands with admin permits
 - `apt` → manage packages sudo apt (update/upgrade/remove/purge)
 - `whoami` → What user am I
 - `ps/ps aux/top` → shows you real time proccesses
 - `systect1` → manages services
 ## 4. Permits
 - r = read 
 - w = write
 - x = execute
 - (type)(owner) (group) (others)
 - -rw-r--r--
 ### FOR CH MOD
 - 4 = Read
 - 2 = Write
 - 1 = Execute
 - 0 = No  permits
 #### EXAMPLES
 - 644 = Owner read and write, Group read, others read
 - 755 = owner full control, group read and execute, other read and execute
 - 600 = owner read and write, group nothin, others nothing
 - 777 everyone can do anything