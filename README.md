# **linux_codes**

Linux is an open-source Unix OS working on the Unix-Kernel.
Linux commands utilizing the CLI(command line interface) like the command prompt in Windows.


## **man** (manual)
**man**  --> Display online manual documentation pages. **apropos, intro, mandoc, manpath, whatis** some other similar commands.

**man ls** --> Details of ls command.


<img width="424" alt="Screenshot 2023-07-10 at 18 35 02" src="https://github.com/EryEr/linux_codes/assets/138815393/3c4bda86-d812-4174-993c-4103464aaf7d">
<img width="1613" alt="Screenshot 2023-07-10 at 18 54 05" src="https://github.com/EryEr/linux_codes/assets/138815393/5212b8b6-2584-4be5-80d5-03a86c6d28a6">


## **mkdir** (make directories)
**mkdir**  --> creates the directories named as operands in the order specified, using mode “rwxrwxrwx” (0777) as modified.

<img width="280" alt="Screenshot 2023-07-10 at 19 20 46" src="https://github.com/EryEr/linux_codes/assets/138815393/0cbc2f93-b476-44c5-9e4d-733ee4232955">


## **touch** (creating a folder)

**touch newDirectory** --> You can see this folder after this command.

<img width="303" alt="Screenshot 2023-07-10 at 19 21 05" src="https://github.com/EryEr/linux_codes/assets/138815393/53e87970-7f28-45ce-b160-3c5d2fe9be7d">

## **cd** (change directory)

**cd newDirectory** --> If there is a folder called newDirectory, you can enter this folder with this command.

**cd ..** ---> You can move one directory up with this command.

**cd**  --> This is diverted directly to the home directory.

**cd -** -->You can return to the previous folder.

<img width="385" alt="Screenshot 2023-07-10 at 19 22 03" src="https://github.com/EryEr/linux_codes/assets/138815393/b4d9062d-eee5-43c5-a83c-6dde1f61ad20">

## **ls** (list)
**ls**  --> Allows to see all the files and folders in the current directory.

**ls -a** --> Showing hidden files additionally.

**ls -lrt**  ---> Allows to see all the files and folders in the current directory. **-l** --> Long, means additional details, **-r** --> reverse order, **-t** sort according to time

**ls -lh**  --> List the content with the size of them

<img width="480" alt="Screenshot 2023-07-10 at 19 26 14" src="https://github.com/EryEr/linux_codes/assets/138815393/c91102f5-56f8-4149-8405-f991a8a814e5">
<img width="542" alt="Screenshot 2023-07-10 at 19 27 42" src="https://github.com/EryEr/linux_codes/assets/138815393/bb4058ff-cf3f-40db-88ad-70490eafa703">

## **rm** (remove directory entries)
**rm**  --> Attempts to remove the non-directory type files specified on the command line.

<img width="496" alt="Screenshot 2023-07-10 at 19 31 50" src="https://github.com/EryEr/linux_codes/assets/138815393/7ba7a79e-bf21-473b-bc7b-4325ace8ae55">

## **rmdir** (remove directories)
**rmdir**  --> removes the directory entry specified by each directory argument. The folder should be empty to be able to remove it.

<img width="377" alt="Screenshot 2023-07-10 at 19 33 54" src="https://github.com/EryEr/linux_codes/assets/138815393/de2ca376-6c8c-492d-ab41-7091fd6b0319">


## **nano, vim** 
**nano, vim**  --> These are text editors. When we start to editing, **i** is allowed to insert then we can add text into the file. **ESC** and **:w** will save the changes. **:q!** exiting without changes.

<img width="487" alt="Screenshot 2023-07-10 at 23 31 39" src="https://github.com/EryEr/linux_codes/assets/138815393/06ca46c2-a2fb-4e31-8bb6-d3c67c63b970"><br>
<img width="478" alt="Screenshot 2023-07-10 at 23 33 12" src="https://github.com/EryEr/linux_codes/assets/138815393/9424f477-094e-44f1-8be9-6ca4bb286b05"><br>
<img width="463" alt="Screenshot 2023-07-10 at 23 33 39" src="https://github.com/EryEr/linux_codes/assets/138815393/59308148-bd66-4a06-9270-766cdf2867f9"><br>
<img width="465" alt="Screenshot 2023-07-10 at 23 34 09" src="https://github.com/EryEr/linux_codes/assets/138815393/ddff1122-b9fd-4516-9109-2d12b8850bee"><br>
<img width="555" alt="Screenshot 2023-07-10 at 23 34 48" src="https://github.com/EryEr/linux_codes/assets/138815393/cd0eed1b-97d3-4d52-b478-d71442063255">



## **cat** (concatenate)

**cat list.txt** --> Allows to see the content of the list file in terminal<br>
<img width="698" alt="Screenshot 2023-07-10 at 23 45 36" src="https://github.com/EryEr/linux_codes/assets/138815393/7e409b2d-4a2a-4be3-b3c6-da34926f0632"><br>

**cat list2.txt lis3.txt > list1.txt** --> Concatenate lis2 and 3 and storing in list1

<img width="325" alt="Screenshot 2023-07-10 at 23 51 17" src="https://github.com/EryEr/linux_codes/assets/138815393/4ee475af-99f2-4ffe-9c30-4c1e8fb857f7"><br>
<img width="532" alt="Screenshot 2023-07-10 at 23 52 34" src="https://github.com/EryEr/linux_codes/assets/138815393/b3e78410-a812-49b9-b908-2eea19fe2f8f"><br>

## **cp** (copy)

**cp list1.txt /home/newDirectory** --> copying the list1 in tothe newDirectory folder.

**cp list1.txt list2.txt** --> creating a new list2 file with same content of list1.
<img width="526" alt="Screenshot 2023-07-10 at 23 58 01" src="https://github.com/EryEr/linux_codes/assets/138815393/fc3feabc-629a-4d74-8493-5a8daa25a636">

**cp . /home/newDirectory** --> copying all current directory content into the newDirectory folder.

**cp -R . /home/newDirectory** --> copying all current directory content with subdirectories(**-R** recursively) into the newDirectory folder.

## **mv** (move)

**mv list1.txt /home/newDirectory** --> instead of copying, moving the list1 in tothe newDirectory folder.


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


## **sudo** (execute a command as super user)
**sudo**  --> allows a permitted user to execute a command as the superuser or another user, as the security policy specifies.

## **chmod** (change mod)
**chmod**  --> modifies the file mode bits of the listed files as specified by the mode operand. Like “rwxrwxrwx” (0777).

## **chown** (change owner)
**chmod**  --> changes the user ID and/or the group ID of the specified files.

## **su** (substitute user identity)
**su**  --> requests appropriate user credentials via PAM and switches to that user ID (the default user is the superuser).  A shell is then executed.





## **df** (display free disk space)
**df**  -->displays statistics about the amount of free disk space on the specified filesystem or on the filesystem of which file is a part

## **du** (display disk usage statistics)
**du**  -->displays the file system block usage for each file argument and for each directory in the file hierarchy rooted in each directory argument

