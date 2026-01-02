#Bandit Level 5 → Level 6

## Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

## Solution
use the find command and different parameters allow you to search for a file that is 1033 bytes in size through the whole directory inhere
find . -type f -size 1033c
### Reconnaissance
Initially, I was pretty confused and ended up on this level longer than I should've. Didn't realize all the "maybehere" are directories so I kept looking through the size of them. 
I eventually googled a command that would let me find a file based on size, so i used the find command. Tried exploring other ways but the find command seemed to be the best.

### Commands Used
```
ls, cd,find
```

### Explanation
This works because the command flags specifies to search for a file in the whole directory AND one that is a size of 1033 in bytes

## Flag
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

## What I Learned
- find command can do -type or -size flag
- c stands for characters and characters are each 1 byte
