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

Task 13-unique:sort | uniq -u: The script takes a list of words as input and prints only words that appear exactly once.

Task 14-findthatword:grep -i root /etc/passwd: The script displays lines containing the pattern “root” from the file /etc/passwd

Task 15-countthatword:grep -i bin /etc/passwd | wc -l: The script displays the number of lines that contain the pattern “bin” in the file /etc/passwd

Task 16-whatsnext:grep -iA 3 root /etc/passwd: The script displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

Task 17-hidethisword: grep -iv bin /etc/passwd: The script displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.

Task 18-letteronly: grep -i "^[a-z]" /etc/ssh/sshd_config: The script displays all lines of the file /etc/ssh/sshd_config starting with a letter.

Task 19-AZ: tr Ac Ze: The script replaces all characters A and c from input to Z and e respectively.

Task 20-hiago: tr -d cC: The script creates a script that removes all letters c and C from input.

Task 21-reverse: rev: The script reverses it's input

Task 22-users_and_homes: cut -d':' -f1,6 /etc/passwd | sort: The script displays all users and their home directories, sorted by users.

Task 23-100-empty_casks: find . -empty -printf "%f\n" : The command finds all empty files and directories in the current directory and all sub-directories.

Task 24-101-gifs: find -type f -name "*.gif" -printf "%f\n" | rev | cut -d'.' -f 2- | rev | LC_ALL=C sort -f : The script that lists all the files with a .gif extension in the current directory and all its sub-directories.

Task 25-102-acrostic: cut -c 1 | tr -d '\n' | sort : The script  decodes acrostics that use the first letter of each line.

Task 26-103-the_biggest_fan: tail -n +2 | cut -f1 | sort | uniq -c | sort -nr | head -11 | tr -s ' ' | cut -d' ' -f3 : The script parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.