# wordle-solver
A simple Python script to solve Wordle

Written in Python 2.7

Intended to be run from the IDLE shell, but you can also run it from a direct command line.

This file is set up to run interactively, with hard mode enabled by default. 
You can disable hard mode by editing the file so the line "hard_mode = True" is changed to "hard_mode = False" instead.

Changing the line "verbose = False" to "verbose = True" will cause the script to print out a lot of information about how it is making decisions.

The normal intended mode is for you to open the Wordle page on your browser, type in the guesses generated by the script, and then type into the script window
the responses from the Wordle page. The responses are enteres as five letter screens indicating the color of each response. 'G' for green, 'Y' for yellow, and 'R' for gray.

You can also uncomment the line "#secret_word = random.choice(solutions)" to have the script run itself against a randomly selected word, or uncomment
the "#secret_word = 'hatch'" line to test against a word that you enter in that line.

The "answers.txt" and "guesses.txt" files are needed to tell the script what the accepted guesses and possible answers are.

I have also included a version of the script that runs against Primel, and a prime number file that it uses instead of the word files.
