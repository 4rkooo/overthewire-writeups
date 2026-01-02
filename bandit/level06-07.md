# Bandit Level 6 → Level 7

## Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

## Solution
find / -type 33c -user bandit7
Searches for a file in the home directory /, that is 33 bytes in size and has the user bandit7 owning the file

### Reconnaissance
First ls shows that there are no directories initially. Accidentally ran cd .. and went into the home user directory for the whole game... I could try running the find command but I want to try exhausting the options where i search using owner permissions. Tried the find command and couldn't find any results. It does say somewhere on the server so I'll try searching from the user directory.

### Commands Used
```
find, cat
```

### Explanation
Searched through the server for a file thats 33 bytes in size and contains bandit7 as the owner

## Flag
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

## What I Learned
- find / will search the home directory (the whole server)
- -user flag can search by which user the owner is of a file
