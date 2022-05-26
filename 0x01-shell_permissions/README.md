Task 0-My name is Betty: Su betty: The script switches the current user to Betty

Task 1-Why am I: id -un: The script prints the effective username of the current user

Task 2-Groups: id -Gn: The script prints all the groups the current user is part for

Task 3-New owner: chown betty hello: The script changes the owner of the file

Task 4-Empty!: touch hello: The script creates an emptry file called hello

Task 5-Execute: chod u+x hello: The scripts gives the owner of the file hello executing permission

Task 6-Multiple permissions: chmod ug+x,o+r hello: The script gives execute permission to the owner and the group owner, and read permission to other users to the file hello

Task 7-Everybody!: chmod a+x hello: The script gived everyone (UGO) executing permissions

Task 8-James Bond: chmod 007 hello: The script gives the other users permission to edit while the Owner and group owner of he file do not have any permissions to either write, read or execute on the file hello.

Task 9-John Doe: chmod 753 hello: The script gives the owner permission to read, write and execute, the group owner permission to execute and read, and the others permission to write and execute

Task 10-Look in the mirror:chmod --reference=olleh hello: The script sets the mode of the file hello the same as olleh’s mode

Task 11-Directories:chmod -R +X .: This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

Task 12-More directories:mkdir -m 751 my_dir: The script creates a directory called my_dir with permissions 751 in the working directory

Task 13-Change group:chgrp school hello: The script changes the group owner to school for the file hello

Task 14-Owner and group:chown vincent:staff *: The script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Task 15-Symbolic links:chown -h staff:vincent _hello: The script changes the owner and the group owner of _hello to vincent and staff respectively.

Task 16-If only:chown --from=guillaume betty hello: The script changes the owner of the file hello to betty only if it is owned by the user guillaume

Task 17-Star Wars:telnet towel.blinkenlights.nl: The script plays the StarWars IV episode in the terminal.