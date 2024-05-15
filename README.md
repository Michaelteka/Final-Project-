ReadME:

This is a simple word guessing game where the player has 10 attempts to guess a randomly chosen word. The game displays the word with underscores for unguessed letters and reveals the letters as they are guessed correctly.

The program runs by:
Entering single alphabetical letters to guess the word.
The player has 10 attempts to guess the word correctly.
The game ends when the word is guessed or attempts run out.

Process:
My first part selects a random word from a predefined list of word and returns a randomly chosen word from the list.
My code creates a display of the word with guessed letters and underscores for missing letters. However, I wasnt able to make the code not reveal the guessed letters without making the game mess up.
I then added comments to describe what the code does.

Code step by step:

The function starts by calling get_word() to get a random word.
I set attempts to 10, which is the number of guesses the player has.
I then print a welcome message
~
The while loop runs as long as attempts is greater than 0.
It calls the display function to show the current state of the word with guessed letters.
It tells the player to enter a letter and converts it to lowercase.
~
It makes sure the input is only a single letter
it also checks if the letter is already guessed 
if it is it prints that it was already guessed
~
If all letters in the word have been guessed it congratulates the player and breaks out of the loop.
If the player runs out of attempts (attempts == 0), it prints a game over message and reveals the correct word.
