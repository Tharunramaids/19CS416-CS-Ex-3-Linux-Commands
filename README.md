# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
![image](https://github.com/user-attachments/assets/88dc62b0-87b8-40c4-bcb5-9f1fc115462a)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
![image](https://github.com/user-attachments/assets/c28db78c-9c2f-419a-b2a6-7223932c1c4e)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/872a2d8e-1f8c-4d94-ba9e-9f0845c469a1)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/7248e03a-9c26-4a10-a53d-6dd0eacf6124)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/3294a489-2208-46bc-b8a5-e341ea38ce5e)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
![image](https://github.com/user-attachments/assets/58a3366a-6baa-4b9f-b751-7dfec73834af)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
![image](https://github.com/user-attachments/assets/f96822c5-1493-4b49-9fb6-92f6ece65f0b)

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/f45327b4-3475-44fc-bc3f-1fa40aa54b5a)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
![image](https://github.com/user-attachments/assets/c3f36087-19f8-4c64-99e8-f608962dc374)


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/96932aa8-9584-4496-9115-b13c43114808)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/450e376d-c0f8-4bc3-90d0-96f9b5cb52ee)

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
![image](https://github.com/user-attachments/assets/c1e18243-616f-430c-a027-111dd53a9945)

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
![image](https://github.com/user-attachments/assets/fd84e9cb-a0ce-48dc-814c-a2ccf0be53b2)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
![image](https://github.com/user-attachments/assets/bba642ee-91f7-4ce9-9ce7-6e197c0f169f)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/13a23f60-25c5-4c15-bf92-7e4095c35365)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
![image](https://github.com/user-attachments/assets/0785eeca-0a5a-42ac-b200-e257b78f6254)

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/c90c7aa8-94b1-4c98-ba11-d2ddace7bfc7)

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
![image](https://github.com/user-attachments/assets/4905fc2b-8162-465e-900b-b76edb0404e1)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
![image](https://github.com/user-attachments/assets/dbff9311-d5d0-46fa-957f-33b5abb8e337)


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
![image](https://github.com/user-attachments/assets/a6a10eae-dea2-4de2-9407-a335040130e8)


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
![image](https://github.com/user-attachments/assets/95c42b0d-b30b-4714-9a9f-bd74f1d82655)



### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/d003ae38-5616-41cf-874a-60fead29cf06)


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
![image](https://github.com/user-attachments/assets/15394c0e-40cc-48c0-8339-c45745005848)


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
![image](https://github.com/user-attachments/assets/796a3394-3cf4-4c98-b558-d66739e8299d)

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
![image](https://github.com/user-attachments/assets/074e3b8f-4e48-45e8-9d57-034c5a09eae6)

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
![image](https://github.com/user-attachments/assets/bb8ceb67-3f2b-4c49-8a2a-93ec6f75e46f)

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/4916d308-1247-4ae9-a2d1-839fe6235257)

## Result
Successfully performed the series of Linux commands as specified.
