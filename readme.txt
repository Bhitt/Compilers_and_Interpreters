# LexAnalyzer

This a program that will perform lexical analysis tokenizing and populating a trie table given a toy program

##Installation

1. Install JLex ver 1.2.6  https://www.cs.princeton.edu/~appel/modern/java/JLex/current/README
	a. Download Link: https://www.cs.princeton.edu/~appel/modern/java/JLex/
	b. JLex Installation Instructions: https://www.cs.princeton.edu/~appel/modern/java/JLex/current/README
2. Move tokenizer.lex and test files to a new folder
3. Move the folder containing JLex into the same folder as the tokenizer.lex and test files(class files and Main.java)
3. In terminal run the following commands:
	a. java JLex.Main LexAnalyzer.lex
	b. ren LexAnalyzer.lex.java LexAnalyzer.java
	c. javac LexAnalyzer.java
	d. java LexAnalyzer "path-to-src-file"

