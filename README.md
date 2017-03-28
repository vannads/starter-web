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

`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

Command | Purpose
-----|---------
ls | List directory contents
ls -a | List directory contents, including directories whose name begins with a dot (.)
ls -l | List directory contents in long format
ls -lh | List directory contents in long format, use unit suffixes (B, K, M, G, T etc.) to reduce the number of digits to 3 or less
ls -lah | same as above, but include directories whose name begins with a dot (.)
ls -t | Sort by time modified (recently modified first) before sorting the operands by lexicographical order
ls -Glp | List directory contents in long format, show a slash ('/') after directory names, and enable colorized output

**Command** | Purpose
-----|---------
ls -g | List directory contents in long format, exclude owner name
ls -go | List directory contents in long format, exclude owner name and group name
ls -goat | List directory contents in long format, including directories whose name begins with a dot (.), exclude owner name and group name, with newest files first
ls -m | List files across the page seperated by commas
ls -l dirName | List contents of the directory, dirName, in long format

>>

**xargs** is a command that takes output of a command and pass it as argument of another command. 

(1) To get a count of number of lines in *.txt* files in the current directory
ls *.txt | xargs wc -l

(2) To zip all *.txt.* files in the current directory
find . -name '*.txt' | xargs zip -9 txt.zip


