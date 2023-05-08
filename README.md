Download Link: https://assignmentchef.com/product/solved-spelling-checker-java
<br>
<u>Program Description:</u>

<u>Spelling Checker</u>

We will create a spell checker program. This program will use this file as a dictionary to look up properly spelled words. When the program starts, you will open the dictionary file (name it “Dictionary.txt”).

You will utilize a hash function you have created to hash the words into an externally-chained hash table you have created. The hash table will be of a size that you will determine. You will then open an input file named “testTextFile.txt.”

When the checking proceeds, you will extract a word from the file to be checked, hash it into the table, and determine if it exists. You will continue this process until you have checked all the words in the file.

Each time you find a word that you cannot match in the dictionary, you will let the user know and you will attempt to generate a list of suggested words. You will generate the list by assembling similar words via three methods:

1.One letter missing. You assume that one letter has been left out of the word.

You can assemble new words to check by adding letters a..z in each of the positions in the word from the start to the end of the word.

2.One letter added. You assume the word has an extra letter. You scan through the word deleting each of the letters in turn, and looking up the word formed by the remaining letters.

3.Two letters reversed. You swap letters in positions 0..1, 1..2, 2..3, … , n-2..n-1, to form new words which you look up. Each time you find a legal word from any of the three methods, you add it to a list of suggestions, which you present to the user when you have finished this part of the process.

If you cannot identify any suggestions, let the user know.