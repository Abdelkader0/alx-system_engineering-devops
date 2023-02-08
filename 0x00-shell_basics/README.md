**Scripts Manual**
=================================================
1. 0-current_working_directory: prints the current working directory and used the command pwd
2. 1-listit: lists the files in the directory used ls for this script
3. 2-bring_me_home: changes the directory to the user's home directory
4. 3-listfiles: Display current directory contents in a long format
5. 4-listmorefiles: Display current directory contents, including hidden files with long format
6. 5-listfilesdigitonly: Display current directory contents in long format and with user and group IDs displayed numerically, and hidden files
7. 6-firstdirectory: creates a directory named my_first_directory in the /tmp/ directory.
8. 7-movethatfile: Move the file betty from /tmp/ to /tmp/my_first_directory
9. 8-firstdelete: Delete the file betty in /tmp/my_first_directory
10. 9-firstdirdeletion: Delete the directory my_first_directory that is in the /tmp directory.
11. 10-back: changes the working directory to the previous one.
12. 11-lists:  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
13. 12-file_type:  prints the type of the file named iamafile in tmp
14. 13-symbolic_link: a symbolic link to /bin/ls, named __ls__
15. 14-copy_html: copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
16. 100-lets_move: moves all files beginning with an uppercase letter to the directory /tmp/u
17. 101-clean_emacs: deletes all files in the current working directory that end with the character ~.
18. 102-tree: creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
19. 103-commas: lists all the files and directories of the current directory, separated by commas (,), Directory names starts with /, Listed directories at the start and sorted the files in alphabitical order
20. school.mgc: detect School data files that starts with string SCHOOL
  ## 0 SCHOOL School data
  ## :!mime School
  >> file -C -m school.mgc
===================================================
