# **linux_codes**

Linux is an open-source Unix OS working on the Unix-Kernel.
Linux commands utilizing the CLI(command line interface) like the command prompt in Windows.


## **man** (manual)
**man**  --> Display online manual documentation pages. **apropos, intro, mandoc, manpath, whatis** some other similar commands.

**man ls** --> Details of ls command.

## **touch** (creating a folder)

**touch newDirectory** --> you can see this folder after this command.

## **cd** (change directory)

**cd newDirectory** --> If there is a folder called newDirectory, you can enter this folder with this command.

**cd ..** ---> You can move one directory up with this command.

**cd**  --> This is diverted directly to the home directory.

**cd -** -->You can return to the previous folder.

## **ls** (list)
**ls**  --> Allows to see all the files and folders in the current directory.

**ls -a** --> Showing hidden files additionally.

**ls -lrt**  ---> Allows to see all the files and folders in the current directory. **-l** --> Long, means additional details, **-r** --> reverse order, **-t** sort according to time

**ls -lh**  --> List the content with the size of them

## **cat** (concatenate)

**cat list.txt** --> Allows to see the content of the list file in terminal

**cat list2.txt lis3.txt > list1.txt** --> Concatenate lis2 and 3 and storing in list1

## **cp** (copy)

**cp list1.txt /home/newDirectory** --> copying the list1 in tothe newDirectory folder.

**cp list1.txt list2.txt** --> creating a new list2 file with same content of list1.

**cp . /home/newDirectory** --> copying all current directory content into the newDirectory folder.

**cp -R . /home/newDirectory** --> copying all current directory content with subdirectories(**-R** recursively) into the newDirectory folder.

## **mv** (move)

**cp list1.txt /home/newDirectory** --> instead of copying, moving the list1 in tothe newDirectory folder.


## **pwd** (present working directory)

**pwd**  --> Showing full path directory of the current directory. 


## **find** 
**find**  --> Walk a file hierarchy. Showing the content of the paths. Care for white spaces.EX:find -x codes\ notes


## **grep** 
**grep**  -->searches any given input files, selecting lines that match one or more patterns

**grep function  Documents/codes\ notes/h002\ alias.txt** --> printing the lines which includes function word


## **head** 
**head**  --> Display the first lines of a file

## **tail** 
**tail**  --> Display the last part of a file

## **diff** (differential file and directory comparator)
**diff mail1.txt mail2.txt**  --> Showing the differences between these two Txt files

## **echo** 
**echo**  --> Write arguments to the standard output. Same role as System.out.println in Java.

## **history** 
**history**  --> Providing the last 500 commands which ran in the terminal. There are many general commands, and this is also one of them.


## **mkdir** (make directories)
**mkdir**  --> creates the directories named as operands in the order specified, using mode “rwxrwxrwx” (0777) as modified.

## **rmdir** (remove directories)
**rmdir**  --> removes the directory entry specified by each directory argument.

## **rm** (remove directory entries)
**rm**  --> Attempts to remove the non-directory type files specified on the command line.

## **sudo** (execute a command as super user)
**sudo**  --> allows a permitted user to execute a command as the superuser or another user, as the security policy specifies.

## **chmod** (change mod)
**chmod**  --> modifies the file mode bits of the listed files as specified by the mode operand. Like “rwxrwxrwx” (0777).

## **chown** (change owner)
**chmod**  --> changes the user ID and/or the group ID of the specified files.

## **su** (substitute user identity)
**su**  --> requests appropriate user credentials via PAM and switches to that user ID (the default user is the superuser).  A shell is then executed.

## **nano, vim** 
**nano, vim**  --> These are text editors.






## **df** (display free disk space)
**df**  -->displays statistics about the amount of free disk space on the specified filesystem or on the filesystem of which file is a part

## **du** (display disk usage statistics)
**du**  -->displays the file system block usage for each file argument and for each directory in the file hierarchy rooted in each directory argument

