Task 0-Hello World: echo Hello, World: The script that prints “Hello, World”, followed by a new line to the standard output

Task 1-Confused smiley: echo "\"(Ôo)'": This scripr prints out the confused smiley

Task 2-hellofile: cat /etc/passwd: The script displays the content of the file /etc/passwd

Task 3-twofiles: cat /etc/passwd /etc/hosts : The scripts diplays the content of two files

Task 4-lastlines: tail /etc/passwd: The script prints the last 10 lines of the file

Task 5-firstlines: head /etc/passwd: The script prints the first 10 lines of the file

Task 6-third_line: head --lines=3 iacta | tail --lines=1: The script displays the third line of the file iacta

Task 7-file: echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)": The shell script creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

Task 8-cwd_state: ls -la > ls_cwd_content: The script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it overwrites it.

Task 9-duplicate_last_line:echo -en "" | tail --lines=1 iacta >> iacta: The script that duplicates the last line of the file iacta

Task 10-no_more_js:find . -name '*.js' -type f -delete: The  script that deletes all the regular files (not the directories) with a .js extension

Task 11-directories: find -mindepth 1 -type d | wc -l: The counts the number of directories and sub-directories in the current directory

Task 12-newest_files: ls -t | head : The script displays the 10 newest files in the current directory