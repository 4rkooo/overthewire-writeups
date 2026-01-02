# Bandit Level 1 → Level 2

## Goal
The password for the next level is stored in a file called - located in the home directory

## Solution
List the contents of the home directory, and then use ./ to refer to the file name since it is a "-"

### Reconnaissance
ls once I remoted into the level, found the file - and used cat, it wouldn't work normally running cat -, so I googled opening cat with a - as the file name since I remembered it being
more specific. I tried running ./cat after some googling and it worked fine.

### Commands Used
```
ls,cat
```

### Explanation
ls will list the contents of the directory and cat will display the contents of a file

## Flag
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## What I Learned
- Files names - cannot just be normally opened, use ./ to refer to them
