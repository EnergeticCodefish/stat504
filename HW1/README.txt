Stat 504 Homework 1
Instructor: Stephen Lee; Student: Ensheng Dong
------------------------------------------------------------------------------------------
ATTENTION:
1. PLEASE READ THIS FILE BEFORE RUNNING SCRIPTS.
2. FOR YOUR CONVENIENCE, PLEASE DOWNLOAD ALL FILES IN THE SAME FOLDER.
------------------------------------------------------------------------------------------
Word Counting Program v 1.2
The first submission is on Friday, Sept 25, 2015
------------------------------------------------------------------------------------------
In this folder (ensheng_stat504/HW1), there are one (1) Python scripts and five (5) test text files: hw1_ex1.py, hw1_ex2.py, hw3_ex3.py; test.txt, bible.txt, newTestament.txt, oldTestament.txt, and words.txt.

Exercise 1 (hw1_ex1.py):
This program will a file, break each line into words, strip whitespace and punctuation from the words, and convert them to lowercase.
Input: any .txt file or the default file: test.txt.
Output: Output_Ex1.txt will be generated in the same folder (ensheng_stat504/HW1 in this case).

Exercise 2 (hw1_ex2.py):
1. Read a file or use the default file oldTestament.txt.
2. Read the number of times of words from the user or 100 by default (k-value).
3. Read the header breaking line defined by the user or the default "*** START OF THIS PROJECT GUTENBERG EBOOK THE KING JAMES BIBLE ***".
3. Print out the output when k=100. Save to Output_Ex2.txt as well. The output is in decreasing order of k.
4. Ask the user whether to test the New Testament. If no, exit the program. If Yes, continue to next step.
5. Read the New Testament file from the user or use the default file newTestament.txt, which contains the same header as the oldTestament.txt.
6. Repeat Step 2 and 3.
7. Print out and save the result to Output_Ex2_new.txt.
8. Check the whole Bible as well.

Exercise 3 (hw1_ex3.py):
1. Read a file or use the default file oldTestament.txt.
2. Read a word list whose words the program will remove from the Exerices 2 result.
3. Read the number of times of words from the user or 100 by default (k-value).
4. Read the header breaking line defined by the user or the default "*** START OF THIS PROJECT GUTENBERG EBOOK THE KING JAMES BIBLE ***".
5. Print out all the words in the Old Testament (or other input files) that are not in the word list.
6. Print out the result as Exercise 2 in Output_Ex3.txt.
------------------------------------------------------------------------------------------
New features in v 1.2:
Update to hw1.ipnb file
------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------
New features in v 1.1:
1. Create test.txt as the default input file for hw1_ex1.py.
2. Provide a suggested input by default.
3. Change the default input file of hw1_ex2.py from bible.txt to oldTestament.txt.
4. Create newTestament.txt for hw1_ex2.py.
5. Debug the input. If the type of the input info is not proper, such as a file path or an integer number (for the k value), a warning will come out.
------------------------------------------------------------------------------------------
Future functions:
1. Creat a funciton to read different txt files.
2. Let the user define the breaking line of the header.
3. Replace the "-" after a word to a space so as to count the number of words more accurately.