# Ex-01-Linux-Commands

# Name:Dharshini.S
# Reg no: 212224230061


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 <img width="1477" height="52" alt="image" src="https://github.com/user-attachments/assets/3dd4e362-3f82-4cac-98db-fc4517d44151" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="322" height="52" alt="image" src="https://github.com/user-attachments/assets/1f10dc7e-7ac8-469f-aae2-9b0c1b3e56a9" />


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <img width="202" height="36" alt="image" src="https://github.com/user-attachments/assets/5147b6c3-61df-42f5-adfd-25eb66853bfd" />



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir 
<img width="225" height="40" alt="image" src="https://github.com/user-attachments/assets/46cfa8fc-c954-4be4-97bb-2414c99efe18" />



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd 
<img width="235" height="27" alt="image" src="https://github.com/user-attachments/assets/494c9f61-39c0-413b-b1f1-d8e91e9d7f37" />



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: 
<img width="191" height="42" alt="image" src="https://github.com/user-attachments/assets/3c605b80-3f47-481c-8f6e-dac99a4f0071" />


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <img width="198" height="88" alt="image" src="https://github.com/user-attachments/assets/2cd12a7b-3447-4d5a-8492-ddb202e8dee4" />




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su 
<img width="261" height="56" alt="image" src="https://github.com/user-attachments/assets/743ba1ac-fff7-4d8c-8a54-422d4912a766" />



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <img width="252" height="292" alt="image" src="https://github.com/user-attachments/assets/ddb5ba04-6f57-438f-89ab-62a4868b2288" />


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="283" height="172" alt="image" src="https://github.com/user-attachments/assets/296178b1-7da1-4942-a7f9-41ac19899bd8" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="256" height="145" alt="image" src="https://github.com/user-attachments/assets/9604fa24-f63d-4798-87a7-5ad8dc601acb" />



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<img width="335" height="142" alt="image" src="https://github.com/user-attachments/assets/c1eb2906-93c2-4fb7-a125-76270b59c90f" />


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="686" height="68" alt="image" src="https://github.com/user-attachments/assets/a721c8ee-e446-412f-bdfa-ff3e85085b5b" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<img width="456" height="177" alt="image" src="https://github.com/user-attachments/assets/990591dd-0df7-4936-8c11-1132f0f0d9da" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="317" height="200" alt="image" src="https://github.com/user-attachments/assets/051f5362-0186-4fc5-a227-69ae827af6be" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="331" height="82" alt="image" src="https://github.com/user-attachments/assets/06b39242-d6a7-4c8a-928a-7a663c6c3176" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
<img width="260" height="177" alt="image" src="https://github.com/user-attachments/assets/6dacbc60-b17e-41cf-bb5a-6621ce7162ec" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="392" height="127" alt="image" src="https://github.com/user-attachments/assets/ac7d587a-8fa1-45b3-9511-4ea64a0630ad" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="255" height="91" alt="image" src="https://github.com/user-attachments/assets/10ca6909-83a9-49c7-a1fb-a5794b6765f1" />



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="510" height="70" alt="image" src="https://github.com/user-attachments/assets/94136730-2645-49d7-ada1-ad516ffcce34" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
<img width="331" height="82" alt="image" src="https://github.com/user-attachments/assets/172ed90c-2930-4de6-bb44-5b594555f6da" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="357" height="72" alt="image" src="https://github.com/user-attachments/assets/8101e878-d2ea-49fb-b363-f921e528e517" />



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
<img width="242" height="73" alt="image" src="https://github.com/user-attachments/assets/ffb221ab-70be-4a8f-a3f9-e83d614d605e" />



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
<img width="262" height="147" alt="image" src="https://github.com/user-attachments/assets/7ddfb1c0-87fb-4bc1-a541-e43640650f46" />


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="232" height="127" alt="image" src="https://github.com/user-attachments/assets/7567e9eb-ff71-497b-a7a2-c5efbef38fa6" />



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="312" height="37" alt="image" src="https://github.com/user-attachments/assets/1ac36e09-0320-43fa-a194-e7499f665df8" />



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="312" height="37" alt="image" src="https://github.com/user-attachments/assets/28947fa6-9022-4739-ba64-3bce7d9cc49d" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df<img width="610" height="215" alt="image" src="https://github.com/user-attachments/assets/0ad93e21-b9b6-4d7d-8c5d-2ad45991a8ed" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”
<img width="218" height="67" alt="image" src="https://github.com/user-attachments/assets/2487da65-c48d-4740-892a-00a370f23267" />

### RESULT:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.






















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
