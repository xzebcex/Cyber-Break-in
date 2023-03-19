# Cyber Break-in
## Description
Cyber Break-in is a command-line minigame in which you take on the role of a hacker trying to get access to a computer system. You must guess the correct password by looking for indications such as the number of correct letters in the password you guessed. You only have a certain amount of chances to guess the correct password.

## Table of content
1.	Prerequisites
2.	Installing and Running
3.	How to Use
4.	Files in the Program
5.	Gameplay
6.	License
7.	How to Contribute
8.	Additional Points
9.	Acknowledgments
10.	Conclusion

## Prerequisites
This script necessitates the installation of Python3 on the user's PC.

## Installing and Running
1.	Clone the repository or download the code files as a ZIP archive.
2.	Navigate to the directory where you downloaded the files.
3.	Open a terminal or command prompt in that directory.
4.	Run the following command: python3 cyber_break_in.py

## How to Use
When you launch the game, you will get a description of the game and be encouraged to hit Enter to begin. As the game begins, you will be shown a "computer memory" display with 12 words. One of these words contains the secret password, which you must guess.
You will be asked to make your first guess. You will be notified how many letters in your guess match the secret password after each guess. You will have a limited number of attempts to guess the right password. You will be allowed access if you guess the right password.

## Files in the Program
cyber break in.py: This is the primary file that includes the game's Python code.
[seven_letter_words.txt]( https://inventwithpython.com/sevenletterwords.txt) 
The program will utilize a list of seven-letter words to generate passwords. You may get this file here, which contains a list of terms that the program may use as passwords.

## Gameplay
As the game begins, the player is given a list of 12 words from which to pick. They must choose one of the words as their password guess. If their guess is incorrect, they are informed of the number of letters in their guess that match the secret password. They will then given a few more chances to accurately guess the password. The game is won if the player guesses the password within the specified number of trials. They lose the game if they do not accurately estimate within the allotted time.

## License
This project is licensed under the MIT License. 

## How to Contribute
This project currently does not require any contributions.

# Additional Points
The game makes use of a collection of seven-letter words from a text file called seven letter words.txt. The game chooses 12 words at random from this list, one of which is the secret password. The "computer memory" display is just artistic and has no bearing on the game mechanics.

## Acknowledgments
This program is inspired by the book "Invent Your Own Computer Games with Python" by Al Sweigart.

## Conclusion
Thank you for using Cyber Break-in. 
