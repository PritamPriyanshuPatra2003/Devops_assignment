**# Linux Commands Assignment 01

## Overview
This repository contains **Assignment 01** on basic Linux commands.  
The purpose of this assignment is to understand and practice commonly used Linux commands for file handling, content viewing, pattern searching, compression, downloading files, permission management, and environment variables.

---

## Objectives
By completing this assignment, the following skills are practiced:

- Creating and renaming files/directories
- Viewing file contents
- Searching for text patterns
- Zipping and unzipping files
- Downloading files from the internet
- Changing file permissions
- Working with environment variables

---

## Assignment Tasks

### 1. Creating and Renaming Files/Directories

#### Commands Used
```bash
mkdir test_dir
touch example.txt
mv example.txt renamed_example.txt
Explanation
mkdir creates a new directory.
touch creates an empty file.
mv renames or moves a file.
2. Viewing File Contents
Commands Used
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
Explanation
cat displays the full contents of a file.
head -n 5 shows the first 5 lines of a file.
tail -n 5 shows the last 5 lines of a file.
3. Searching for Patterns
Command Used
grep root /etc/passwd
Explanation
grep searches for lines containing a specific word or pattern.
In this case, it searches for the word root inside /etc/passwd.
4. Zipping and Unzipping
Commands Used
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir
Explanation
zip compresses files or directories into a .zip archive.
unzip extracts the contents of a .zip archive into a specified directory.
5. Downloading Files
Command Used
wget https://example.com/sample.txt
Explanation
wget is used to download files from the internet using a URL.
Since the provided example URL was not valid for actual download, another test URL such as Wikipedia was also checked.
6. Changing Permissions
Commands Used
touch secure.txt
chmod 444 secure.txt
Explanation
touch creates an empty file named secure.txt.
chmod 444 sets the file permission to read-only for everyone.
7. Working with Environment Variables
Commands Used
export MY_VAR="Hello Linux!"
echo $MY_VAR
Explanation
export creates an environment variable.
echo prints the value stored in that variable.
Learning Outcome

This assignment helped in understanding the fundamentals of Linux command-line operations, including:

File and directory management
Content inspection
Pattern matching
Archive handling
Network-based file downloading
Permission settings
Shell environment variable handling
Repository Structure
.
├── README.md
└── assign1.docx
Author

Pritam Priyanshu Patra

License

This project is created for educational purposes.


