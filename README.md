# Hangman
Hangman is a popular word guessing game where the player attempts to build a  missing word by guessing one letter at a time. After a certain number of  incorrect guesses, the game ends and the player loses.
The game also ends if the player correctly identifies all the letters of the missing word. The game is realized using the already known term which is to be guessed. At the beginning 
of the game, the player tries to guess the term by writing letters from the 
standard input. If the entered letter does not exist in the specified term, then the 
part of Hangman is added. However, if the letter exists in the term which a 
player tries to guess, then the letter is written to the appropriate position in the 
word. If the letter has already been hit, the user is informed necessarily about it, 
and if the user by accident writes it, then it does not affect the game. Every time 
a new letter is entered from the standard input, it is necessary to print it on the 
screen. When a user guesses the current term, they are allowed to hit the new 
one. If the user misses the letters enough times, the entire Hangman is drawn 
out, and a player loses the game
