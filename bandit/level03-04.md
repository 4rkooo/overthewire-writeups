# Bandit Level 3 → Level 4

## Goal
The password for the next level is stored in a hidden file in the inhere directory.

## Solution
cd into the inhere directory, and use ls with the flag -a to find ALL files (including hidden ones) and cat the hidden file

### Reconnaissance
I used ls -a to be safe on the home directory, then i changed into the inhere directory and used the same command to find the hidden file with the flag

### Commands Used
```
ls, cat
```

### Explanation
-a flag when using ls is to list hidden files

## Flag
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## What I Learned
- Flag to display hidden files in a directory
