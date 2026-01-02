# Bandit Level 8 → Level 9

## Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

## Solution
sort -f data.txt | uniq -u

### Reconnaissance
Did a cat on the file, but there are way too many lines. Going to see if theres a flag that can helped.

### Commands Used
```
sort, unique
```

### Explanation
Used sort command first with -f command to sort while ignoring all upper or lowercase, then piped that output into the input of unique where I found the unique input using -u  out of all
those entries

## Flag
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

## What I Learned
- Sort command
- Unique command
