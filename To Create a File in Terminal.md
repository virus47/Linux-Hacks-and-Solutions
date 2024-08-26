1. Create a file in the Linux/Unix system using the touch command. 

$ touch newfile.txt

$ touch [option] ... FILE...

A brief description of options available in the touch command.

Option 	                Description
-a 	                    Change the access time of a file
-c, –no-create 	        Check file is available or not, if not available then prevent creating a file 
-f 	                    ignored
-m 	                    Change the modification time of a file
-t STAMP 	            Use specified time instead of the current time
–help 	                Display help and exit
–version 	            Display the version information and exit.


2. Create a File in the Linux/Unix system using the cat command.

$ cat > file.txt

$ cat [option]... FILE...

Option 	                Description 
-A, –show-all 	        Show all content of a file
-b, –number-nonblank 	Display number of non-empty lines overrides -n
-n, –number 	        Display number of all output lines
-T, –show-tabs 	        Display this help and exit
–help 	                Display this help and exit
–version 	            Display version information and exit


3. Create a file in the Linux/Unix system using a redirection operator. 

$  > file.txt


4. Create a new file without contents in the Linux system using the echo command.

$ echo > file.txt

Create a new file with some contents in the Linux system using the echo command. 

$ echo "Hello WOrld" > file.txt


5. Create a file in the Linux/Unix system using heredoc.

heredoc stands for here document. The heredoc delimiter is a type of redirection. It allows passing multiple lines of input to a command. 

Command << Heredoc_delimiter
multiple lines contents...
heredoc_delimiter

Create a file with multiple lines of contents using a heredoc delimiter in the Linux system. 

$ cat  << heredoc_delimiter < file_name


6. Create a file in the Linux/Unix system using the dd command.

The dd command is mainly used to converts and copy files. To check more details about the dd command. We can also create a large file using the dd command.

$ dd if = /dev/zero of = file.test bs =1 count =0 seek = 2G

