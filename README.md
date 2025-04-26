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

![image](https://github.com/user-attachments/assets/c55dd3b5-f6b6-4eae-b632-d97f1243257b)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

![image](https://github.com/user-attachments/assets/be208d8d-5f2d-470e-a410-833ce3c71c2a)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/46c4a307-853c-4e63-bd38-3ee7029e5e5d)

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/563fb4ac-6c68-4b8f-a0b5-8ed2b5197b24)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/28c4880d-daff-409e-9120-3ee580c97b91)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

![image](https://github.com/user-attachments/assets/56ab0be4-ef5b-48ab-af8a-7afcd994ce27)



### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

![image](https://github.com/user-attachments/assets/fa68233a-5be0-4548-b9d9-be3fd3692731)

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/b571b049-f1ef-48b7-9e39-4400e93f783e)

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

![image](https://github.com/user-attachments/assets/b3686a90-95c3-490a-ac43-74216504b7f7)


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

![image](https://github.com/user-attachments/assets/64828a4c-159f-4f1b-907e-bd3d428d7fba)

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

![image](https://github.com/user-attachments/assets/d4670d5d-5069-4a94-888d-62ae3fc26585)

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/3ee188d3-cf58-4f5d-8a8f-d4d0649317da)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/447c1ee1-3a67-4519-86d7-822476f94868)


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

![image](https://github.com/user-attachments/assets/8038d9d5-431c-4285-90ac-634d10842204)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

![image](https://github.com/user-attachments/assets/a9166abc-6ffd-441c-b07b-1f5c658926f5)

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

![image](https://github.com/user-attachments/assets/0a29ae3a-4d11-458c-b869-29874e083e12)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/8d679d71-9179-4819-abe5-51b54cdb9ef8)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

![image](https://github.com/user-attachments/assets/26239f0f-6ef2-4551-90f3-fc50d9a427b5)


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/de9d91ef-657e-498f-a9f9-d99d0b93cbfb)

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

![image](https://github.com/user-attachments/assets/6bb6eddc-db7a-4d30-96ec-304c1a061a55)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

![image](https://github.com/user-attachments/assets/d0f2a8fb-ee9d-4355-9e95-dc66a6e5a4e3)


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

![image](https://github.com/user-attachments/assets/25e6c27c-5f9a-45c9-8335-0835cce833e6)


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

![image](https://github.com/user-attachments/assets/c3af872c-19f0-49a0-8a0e-77dcd37f7924)


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

![image](https://github.com/user-attachments/assets/61f8d04c-6a87-493a-ad7a-279333fd2b9a)


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/250f2f6a-d2ec-4c75-97c8-39b40125a8c3)


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

![image](https://github.com/user-attachments/assets/23ef2ecb-605c-4aff-9ead-15d74da450e6)


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

![image](https://github.com/user-attachments/assets/e4dadcb1-a6c9-4dc4-b24d-4bc3db1db7da)


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

![image](https://github.com/user-attachments/assets/febdcd7a-8620-4fff-9826-b9026d569abe)


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

![image](https://github.com/user-attachments/assets/eb48659a-1156-4fca-9c33-12ba0f74f9fc)


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/97177a7d-8474-4378-9594-ff596549a558)


## Result:
Thus,Linux commands covers some basic and advanced commands used in Linux are executed in the terminal successfully.
