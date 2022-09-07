alias ls="rm *" is script that creates an alias.
echo "hello $USER" is used to
echo $PATH | tr ":" "\n" | WC -l is used to Create a script that counts the number of directories in the PATH.
printenv is used to Create a script that lists environment variables.
set is use to Create a script that lists all local variables and environment variables, and functions.
export BEST="School" is used to Create a script that creates a new local variable.
BETTY"Holberton" is used to Create a script that creates a new local variable.
export HOLBERTON="Betty" is used to Create a script that creates a new global variable
echo $(($TRUEKNOWLEDGE+128)) is used to Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $((POWER/DIVIDE)) is used to Write a script that prints the result of POWER divided by DIVIDE, followed by a new line
echo $(($BREATH**LOVE)) is used to Write a script that displays the result of BREATH to the power LOViE
echo "$((2#$BINARY))" is used to Write a script that converts a number from base 2 to base 10.
echo {a..z}{a..z} | tr ' ' '\n' grep -v "oo" is used to Create a script that prints all possible combinations of two letters, except oo.
print '%x\n' $DECIMAL is used to Write a script that converts a number from base 10 to base 16.
tr 'A-Za-z' 'N-ZA-Mn-za-m' is used to Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.
paste - - | cut -f1 is used to Write a script that prints every other line from the input, starting with the first line.
printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stir. 01234) )) | tr 01234567 bestchol is used to Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.
