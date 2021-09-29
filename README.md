# Pscine2021

******************************

#ex02
--------------
*How To Create Files Of A Certain Size In Linux / 
https://ostechnix.com/create-files-certain-size-linux/ 

1.
$ truncate -s 5M ostechnix.txt
The above command will create a file called ostechnix.txt with size exactly 5MB. 
$ truncate -s 1 os
The above command will create a file called os with size exactly 1 byte.

2. 
fallocate 
3. 
head
4. 
dd
--------------
*Explaining Soft Link And Hard Link In Linux With Examples
https://ostechnix.com/explaining-soft-link-and-hard-link-in-linux-with-examples/  



---------------
modify-change-timestamps-and attributes.. / https://www.shellhacks.com/fake-file-access-modify-change-timestamps-linux/

$ touch -a --date="1988-02-15 01:00" file.txt 
$ touch -m --date="2020-01-20 23:05" file.txt
-a access time , -m modify time 
-------------------

Changing the timestamp of a symlink
https://unix.stackexchange.com/questions/63876/changing-the-timestamp-of-a-symlink

add switch -h

$ touch -h -t 201301291810 myfile.txt


-----------------

*File permissions and attributes

https://wiki.archlinux.org/title/File_permissions_and_attributes

---------------

************************************
#ex03

$ ls -pmu 

place the command line that will list all files and directories in your
current directory (except for hidden files or any file that starts by a dot - yes, that
includes double-dots), separated by a comma, by order of access time. Make sure
directories’ names are followed by a slash character.

$ ls --help 
$ man ls

------------------------

*********************************************

#ex04

commit history of git 

https://www.poftut.com/how-to-list-commit-history-with-git-log-command-with-examples/

https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History


Another really useful option is --pretty. This option changes the log output to formats other than the default. 

The most interesting option value is format, which allows you to specify your own log output format. This is especially useful when you’re generating output for machine parsing — because you specify the format explicitly, you know it won’t change with updates to Git:

$ git log --pretty=format:"%h - %an, %ar : %s"
ca82a6d - Scott Chacon, 6 years ago : Change version number
085bb3b - Scott Chacon, 6 years ago : Remove unnecessary test



Table 1. Useful specifiers for git log --pretty=format
Specifier	Description of Output
%H

Commit hash

%h

Abbreviated commit hash

%T

Tree hash

%t

Abbreviated tree hash

----------------------------------
*************************************************************

#ex05
