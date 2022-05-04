# New-project
A password strength evaluator
A program that evaluates potential passwordsmto determine how strong they are.
The program includes the following four functions:
check_length - This function should accept a password to evaluate as a parameter and should
return a score based on the length of the password. A password that is less than 8 characters
long gets a length score of 1. If it is between 8 and 11 characters long (inclusive), it gets a length
score of 2. A password that is 12 characters or longer gets a length score of 3.

check_case - This function should accept a password to evaluate and return a case score of 1
or 2. If the letters in the password are all uppercase or all lowercase, the case score should be
a 1. If there is a mix of uppercase or lowercase letters (or if there are no letters at all), it gets a
case score of 2.

check_content - This function should accept a password to evaluate and return a content
score. If the characters are all alphabetic characters, the content score is 1. If the characters
include any numeric digits (either all numeric or a mix of letters and digits), the content score is
2. If there are any other types of characters (such as punctuation symbols), the content score is
3.

main - This function represents the main program. It accepts no parameters and returns no
value. It contains the loop that allows the user to process as many passwords as desired. It calls
the other functions as needed, computing the overall score by adding up the scores produced
by each function. All output should be printed in the main function
