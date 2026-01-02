# Bandit Level 2 → Level 3

## Goal
The password for the next level is stored in a file called --spaces in this filename-- located in the home directory

## Solution
ls, cat ./-- spaces in the filename--

### Reconnaissance
Listed the files in home directory, used cat on the only one there, used ./ once again due to the dashes in the name

### Commands Used
```
ls, cat ./[filename]
```

### Explanation
[Why this worked]

## Flag
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## What I Learned
./ is more effective with files using any type of dashes
