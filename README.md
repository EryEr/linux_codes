# **linux_codes**

Linux is an open-source Unix OS working on the Unix-Kernel.
Linux commands utilizing the CLI(command line interface) like the command prompt in Windows.

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


