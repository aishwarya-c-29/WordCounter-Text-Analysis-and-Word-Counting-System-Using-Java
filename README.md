# WordCounter

# Description
Word-Counter is a Java program that searches for specified words in a given text file and counts their occurrences. It provides a simple yet powerful command-line interface with several features, including searching for multiple words at once.

To use the program, simply provide the name and path of the text file to search and the word(s) to look for as command-line arguments. The program will then search for occurrences of the specified words in the file and print the results to the terminal.

If either argument is missing, the program shows an output message describing the correct usage. If the specified file does not exist, it displays an error message indicating that the file was not found.

The program also supports searching for multiple words at once. When multiple words are specified, the results are displayed in a table format, with columns for each word and their respective counts. The table view is dynamically sized to fit the longest word and count.

Overall, Word-Counter provides a simple yet effective way to search for and count words in text files.

# Installation and Usage
My program has the following features :

• Accept two arguments from the command line. – The first argument is the name (and path) of the file containing the text. – The second argument is the word that is being searched for.

– If either argument is missing, it shows output of the following message: Usage:  java WordCounter   

– If the specified file does not exist in the given location, it's output is of :  File not found:
followed by a space and the name of the file. 

To install :

Clone the repository and run the program using the following command:
Compile the program using the following command in src folder :  javac *.java 
Run the program using the following command in src folder :  java WordCounter filename searchTerm 
Features
– Searches through the file for occurrences of the specified word. – The word should only be counted when it appears as a whole word. For example, when searching for hope , the word orthopedic does not count as a match. – To keep things simple, a word is defined as a continuous sequence of characters from the ranges A–Z, a–z, 0–9, and the underscore ( _ ) character. All other characters are to be ignored. Hence, they're counted as two separate words. – Printing the results to the terminal. – The message printed has the form “The word ‘’ appears time(s).”

For example:
The word 'animal' appears 17 times.

The word 'lugubrious' appears 1 time.

Support searching for multiple words at once.

All command-line arguments from the second argument onwards are treated as words to search for.

If multiple words are specified, instead of printing the message specified above, the results are shown as a table in the following form:

The columns in this view adapts to the lengths of the words and numbers shown: they should be wide enough to display all words and numbers with at least one space on either side, as shown.

Words and column-headers should be left-aligned, while numbers should be right-aligned.

WORD	COUNT
round	17
ability	0
enemy	1
TOTAL	18

# Learning Outcomes
Understanding of string manipulation in Java
Implementation of data structures (like HashMap)
Basic text processing techniques
Writing clean and modular code

# Future Enhancements
GUI version using Java Swing / JavaFX
File upload support
Stop-word removal
Integration with NLP libraries
