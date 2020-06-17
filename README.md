# Hangman_Game

In this, there is a separate file named ‘words.txt’ which contains different
words related to the concepts in python (eg. List, string, dictionary etc).
We have used basic file operations such as open, read etc. to use the
words in our program.

# REMEMBER:
>The category of words in this game is CONCEPTS IN PYTHON.

The program will prompt the user to guess a letter. There is a list of
alphabets from which user will select appropriate letter. According to the
selection made, the program responds in the following way:

1] If the user selected a letter, which is present in the word, it will fill that
letter in the word.
2] If the selected letter is wrong, then a chance is reduced. There are
total 7 chances for the user to guess. The chances will decrease if the
user enters a wrong letter.
3] On reaching the second last chance, the user will get a hint of a letter
in the word which is not yet guessed by the user. But, along with the hint,
1 chance is reduced from the chances left.
4] If the user enters 2 letters in a single chance or repeats a letter which
he already guessed previously, then appropriate messages are displayed.
Also, chances are not reduced in such cases.
5] The set of remaining alphabets are displayed for user’s reference.
6] Whether or not, the user is successful in guessing the word, he will
have the option of playing the game again.
