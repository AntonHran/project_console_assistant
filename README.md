Personal console assistant

Project description:
The console assistant is a program that consists of three blocks and provides the user with functionality to manage the notebook, clean up files, and play Hangman.

Notebook block:
- The notebook contains contacts with fields: name, phone list, email, date of birth, status and notes.
- The user can add new contacts, edit the fields of existing contacts, delete contacts, view how many days are left until the contact's birthday (provided there is an entry in the date of birth field), search by keyword in all contact fields, display a list of contacts with all fields and output a separate contact field by the specified name.

Cleaning block:
- The block allows you to sort files in the specified directory by their extension.
- The program scans all files in the specified directory, including files in folders and subfolders.
- Each file is analyzed by its extension and moved to one of the new folders according to the file type.
- If the file extension does not match any of the folders, the file is moved to the "Other" folder.
- After sorting, empty folders are deleted.

Entertainment block:
- The block contains the game "Hangman" where the user has to guess a random word by indicating one letter for each turn.
- The game has a score that shows the number of wrong answers.
- In case of incorrect answer, images symbolizing step-by-step "hanging" of the player appear.

Instructions and requirements:
- Each block has its own instructions that explain the available commands and their use.
- The program implements validation of mail, phone numbers, directory, status, and the presence of a contact's name.
- The program also includes error and exception handling to ensure stable operation and clear error messages to the user.

Installation and use:
1. Install the necessary packages using the dependencies file (poetry.lock).
2. Run the program using the command line or other appropriate interface.
3. Follow the instructions provided in the console to use the various functions and blocks of the program.

License: None

Program expansion and improvement

Description of the idea:

1. Add a new game "Tic-Tac-Toe" to the entertainment block of the program. The user can choose the game mode: "Two players" where you can play with another person, or "Auto" where the user plays with the program.
2. Consider adding a GUI developed using Tkinter to the assistant so that the program is not limited to a console application.
3. Add separate interfaces for each game to ensure convenient and intuitive use.