
------------
# Scripts Manual &copy;

##### " 0-current_working_directory "
###### prints the current working directory using the pwd command.

------------


##### " 1-listit "
###### lists the files in the current directory using the ls command.
------------

##### " 2-bring_me_home "
###### changes the current directory to the user's home directory using the cd command.
------------

##### " 3-listfiles "
###### displays the contents of the current directory in long format using the ls -l command.
------------

##### " 4-listmorefiles "
###### displays the contents of the current directory, including hidden files, in long format using the ls -la command.
------------

##### " 5-listfilesdigitonly "
###### displays the contents of the current directory, including hidden files, in long format with the user and group IDs displayed numerically using the ls -lna command.
------------

##### " 6-firstdirectory "
###### creates a directory named my_first_directory in the /tmp/ directory using the mkdir command.
------------

##### " 7-movethatfile "
###### moves the file betty from /tmp/ to /tmp/my_first_directory using the mv command.
------------

##### " 8-firstdelete "
###### deletes the file betty in /tmp/my_first_directory using the rm command.
------------

##### " 9-firstdirdeletion "
###### deletes the directory my_first_directory in the /tmp/ directory using the rmdir command.
------------

##### " 10-back "
###### changes the current directory to the previous one using the cd - command.
------------

##### " 11-lists "
##### lists all files, including hidden ones, in the current directory, the parent of the current directory, and the /boot/ directory, in long format, using the ls -la command.
------------

##### " 12-file_type "
###### prints the type of the file named iamafile in /tmp/ using the file command.
------------

##### " 13-symbolic_link "
###### creates a symbolic link to /bin/ls named __ls__ using the ln -s command.
------------

##### " 14-copy_html "
###### copies all HTML files from the current directory to the parent of the current directory, only if they do not exist or are newer in the parent directory, using the cp command and the -u option.
------------

# ADVANCED
##### " 100-lets_move "
###### moves all files starting with an uppercase letter to the directory /tmp/u using the mv command and the [A-Z]* pattern.
------------

##### " 101-clean_emacs "
###### deletes all files in the current directory ending with the character ~ using the rm command and the *~ pattern.
------------

##### " 102-tree "
###### creates the directories welcome/, welcome/to/, and welcome/to/school in the current directory using the mkdir command.
------------

##### " 103-commas "
###### lists all files and directories of the current directory separated by commas (,), directory names starting with /, and listed directories first, sorted in alphabetical order, using the ls -l command and the sort command.
##### school.mgc : detects School data files
###### - 0 string SCHOOL School data
###### - !:mime School
>>file -C -m school.mgc

