# Hangman Solver

This repository contains a Jupyter Notebook (`HangmanSolver.ipynb`) that implements a Hangman game solver. The solver is designed to help you find the correct word when playing Hangman by making educated guesses based on the revealed letters and guessed letters.

## How to Use

1. Open the `HangmanSolver.ipynb` notebook in a Jupyter Notebook environment.

2. Run the notebook to load the necessary functions and data.

3. The solver will interactively ask you for information about the Hangman puzzle:

   - Input the revealed word with "-" representing unknown letters.
   - Input the guessed letters in the form "abcd" (e.g., "aeiou") to specify which letters have already been guessed.

4. The solver will then provide a list of potential words that match the given criteria. These words are sorted by the likelihood of each letter in the alphabet being in the solution.

5. Continue running the solver by inputting more revealed letters and guessed letters until you are confident in the solution.

6. When you believe you have solved the puzzle, type "y" to indicate that the game is solved.

## Data File

This Hangman Solver uses a data file named `words_dictionary.json` located in the repository. This file contains a dictionary of words and is used for word matching. Make sure you have this file in the same directory as the notebook.

## License

This Hangman Solver is provided under the MIT License. Feel free to use, modify, and distribute it as needed.

Happy Hangman solving!
