# Māori Diceware Word List

For the word list see: https://github.com/Taipo/MaoriDiceware/blob/master/diceware_maori.txt

The aim is to create a pass phrase of 7 or more words from the Māori word list above.

An example pass phrase is: korehu tipu kotiro rewena kanohi hitori aotea

##Instructions

1/ Roll a dice 5 times and recording each roll creates a 5 digit number,  example 5 rolls resulting in 2, 6, 4, 2, 1 combined together make the number = 26421

2/ Go to the word list and find the word associated with 26351 = korotangi, this becomes your first word.

3/ Repeat this until you have generated at least 6 words.

##The Math

6 words from a word list of 7776 words: log2(7776^6) = 77.54 bits

7 words from a word list of 7776 words: log2(7776^7) = 90.47 bits

8 words from a word list of 7776 words: log2(7776^8) = 103.39 bits

9 words from a word list of 7776 words: log2(7776^9) = 116.32 bits

10 words from a word list of 7776 words: log2(7776^10) = 129.24 bits
