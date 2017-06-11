# Māori Diceware Word List
For the word list see: https://github.com/Taipo/MaoriDiceware/blob/master/diceware_maori.txt

The aim is to create a pass phrase of 7 or more words from the Māori word list above.

An example pass phrase is: korehu tipu kotiro rewena kanohi hitori aotea

## Instructions
1/ Roll a dice 5 times and recording each roll creates a 5 digit number,  example 5 rolls of 2 6 3 5 1 = 26351

2/ Find the word associated with 26351 = korehu, this becomes your first word.

3/ Repeat this until you have generated at least 7 words.

## The Math
7 words from a word list of 7776 words: log2(7776^7 /2) = 89.47 bits

8 words from a word list of 7776 words: log2(7776^8 /2) = 102.39 bits

9 words from a word list of 7776 words: log2(7776^9 /2) = 115.32 bits

10 words from a word list of 7776 words: log2(7776^10 /2) = 128.24 bits
