Task 0-alias: alias ls="rm *" : The script creates an alias

Task 1-hello_you: echo hello $USER : The script prints hello user where user is the current linux user

Task 2-path : export PATH=$PATH:/action : The script adds /action to PATH.

Task 3-paths : echo $PATH | tr -s ":" "\n" | wc -l : The script counts the number of directories in the PATH

Task 4-global_variables : printenv : The script lists all environment variables

Tast 5-local_variables : set : The script lists all local variables and environment variables, and functions.

Task 6-create_local_variable : BEST="School" : The script creates a new local variable

Task 7-create_global_variable : export BEST="School" : The script creates a new global variable

Task 8-true_knowledge : echo "$((TRUEKNOWLEDGE+=128))" : The script prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

Task 9-divide_and_rule: echo $((POWER/DIVIDE)) : The script prints the result of POWER divided by DIVIDE, followed by a new line.

Task 10-love_exponent_breath : echo $((BREATH**LOVE)) : The script displays the result of BREATH to the power LOVE

Task 11-binary_to_decimal : echo "$((2#$BINARY))" : The script converts a number from base 2 to base 10.

Task 12-combinations : printf "%s\n" {a..z}{a..z} | grep -v "oo" : The script prints all possible combinations of two letters, except oo.

Task 13-print_float : printf "%.2f\n" $NUM : The script prints a number with two decimal places, followed by a new line.

Task 100-decimal_to_hexadecimal : printf "%x\n" $DECIMAL : The script converts a number from base 10 to base 16

Task 101-rot13 : tr 'a-zA-Z' 'n-za-mN-ZA-M' : The script encodes and decodes text using the rot13 encryption. It assumes ASCII.

Task 102-odd : cat -n | grep [13579][[:space:]] | tr -s ' ' | cut -f2 : The script prints every other line from the input, starting with the first line.

Task 103-water_and_stir : printf "%o\n" $((5#`echo $WATER | tr 'water' '01234'` + 5#`echo $STIR | tr 'stir.' '01234'`)) | tr '01234567' 'behlnort' : The script adds the two numbers stored in the environment variables WATER and STIR and prints the result.