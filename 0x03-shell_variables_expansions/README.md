Task 0-alias: alias ls="rm *" : The script creates an alias

Task 1-hello_you: echo hello $USER : The script prints hello user where user is the current linux user

Task 2-path : export PATH=$PATH:/action : The script adds /action to PATH.

Task 3-paths : echo $PATH | tr -s ":" "\n" | wc -l : The script counts the number of directories in the PATH

Task 4-global_variables : printenv : The script lists all environment variables