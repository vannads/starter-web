# Starter Web Repo

This repository is for showing how Git and GitHub work

## Purpose

Sample website with plenty of files for demos

show current working directory path
creating a directory
deleting a directory
creating a file using touch command
deleting a file
renaming a file
listing hidden files
copying a file from one directory to another

Task | Command | Notes/example result
-----|---------|-------
Show current working directory path | pwd | /Users/svannadil
Creating a directory | mkdir temp00 | Creates temp00 under /Users/svannadil
Deleting a directory | rmdir temp00 | Removes temp00 under /Users/svannadil
Creating a file using touch command | touch test.txt | Creates a new empty file test.txt, if exists update modification date
Delecting a file | rm test.txt | Removes test.txt
Renaming a file | mv test.txt test01.txt | Renames test.txt as test01.txt
Listing hidden files | ls -a | List all, including hidden files
Copying a file from one directory to another | cp temp01/test01.txt temp02/ | Copies file test01.txt from directory temp01 to directory temp02
Copy multiple files into a directory | cp file1.txt file2.py file3.js target/ | Copies file1, file2, and file3 into directory target/
Recursively copy from one directory to another | cp -R source/ target/ | Recursively copies from source/ to target/ 

