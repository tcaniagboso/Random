# Random Projects I have been Working on

The first one is a 'Spell-Checker' application that takes in a text-file as an input. The text file and the program must be in the same directory in the computer’s 
library for the text file to be read and written to by the program. An error message will be displayed if the text file and program are not in the same directory. 
The program makes use of an installed English dictionary package to determine if a given word exists in English language. The Spell-Checker application runs through 
every word in a text file one by one and determines if it exists in the English dictionary or not.  Once the program spots a word that doesn’t exist in the English 
Dictionary Package, it assumes that the word is misspelled and makes suggestions to the user. The user now has the option to accept or ignore the suggestions by 
answering ‘Y’ or ‘N’. If the user answers ‘Y’ the program replaces the misspelled word in the file with the new word, but if the user continuously answers ‘N’ for a 
certain word, the program suggests other possible replacements until it runs out of possible replacements, then leaves the word the way it is and moves on to the next 
misspelled word. When the program is done reading and writing to the file, it creates an updated text file with the corrected spellings and asks the user if they would 
like to run the program on another text file. If the user answers ‘Y’ the program will ask for the name of the text file, but if the user answers ‘N’ the program will 
stop running. 
