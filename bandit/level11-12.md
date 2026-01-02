# Bandit Level 11 → Level 12

## Goal
The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

## Solution
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'  

### Reconnaissance
Checking the article linked, tr is used to implement ROT13, gonna look into that more. I could try manually translating the letters by hand,
but I'm going to look for a way to decrypt using tr. Ended up googling. 

### Commands Used
```
cat, tr
```

### Explanation
This works because of piping, we use the cat on the ROT13 phrase to produce the output, which is then an input for the next command tr, which
will decode the phrase.

## Flag
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

## What I Learned
- Decoding files with ROT13 data
- Using the command tr.
