# Bandit Level 10 → Level 11

## Goal
The password for the next level is stored in the file data.txt, which contains base64 encoded data

## Solution
base64 -d data.txt

### Reconnaissance
First I tried to cat the file normall. I almost tried this as the key but saw the base64 encoded specification, so I looked into the base64 command and its flags.

### Commands Used
```
base64
```

### Explanation
base64 has the -d flag which will decode the file specified

## Flag
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

## What I Learned
- Base64 command
- Decoding files with base64 data
