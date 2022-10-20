# Linux-File-Directory-Permissions



1.	Create a directory bsseA _permission_test in /home/[username] directory.
2.	Cd into bsseA _permission_test.

3.	Create a file data.txt using following command:
-	echo “This is a test file to inspect and modify  permissions” > data.txt

4.	Check the content of data.txt using following command:
-	cat data.txt

5.	 create a dirA in pwd using “mkdir dirA” command

6.	Check default permissions of dirA and data.txt using ls –l commad

7.	Change the permission of data.txt using octal digits as
-	All users can only read and write [confirm using ls –l ]
-	Only group can read write and execute [confirm using ls –l ]


8.	Change the permission of dirA using octal digits as
-	owner can only execute and write & group can read and execute & other can read and write  [confirm using ls –l ]	
-	Owner and other  can read and  execute [confirm using ls –l ]	

9.	Set permissions of data.txt using symbol to:  
-	–rw-rw----
-	–rwx rwx rwx
-	-rw-rw-rw-

10.	Set permissions of dirA using symbol to:
-	–rw-rw---x
-	–rwxr-xr-x
-	--w-r--rw-

