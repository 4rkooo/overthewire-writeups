# Bandit Level 12 → Level 13

## Goal
The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

## Solution


### Reconnaissance
So the file is compressed and is also a hexdump. Used gzip to uncompress it and the file now looks like something I've seen before, although random numbers and letters. Need to find a way to make the gz file readable.

### Commands Used
```
mkdir, xxd, 
```

### Explanation


## Flag


## What I Learned
- 
- 
