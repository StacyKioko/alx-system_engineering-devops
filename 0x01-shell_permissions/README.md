Task 0-My name is Betty: Su betty: The script switches the current user to Betty

Task 1-Why am I: id -un: The script prints the effective username of the current user

Task 2-Groups: id -Gn: The script prints all the groups the current user is part for

Task 3-New owner: chown betty hello: The script changes the owner of the file

Task 4-Empty!: touch hello: The script creates an emptry file called hello

Task 5-Execute: chod u+x hello: The scripts gives the owner of the file hello executing permission

Task 6-Multiple permissions: chmod ug+x,o+r hello: The script gives execute permission to the owner and the group owner, and read permission to other users to the file hello

Task 7-Everybody!: chmod a+x hello: The script gived everyone (UGO) executing permissions