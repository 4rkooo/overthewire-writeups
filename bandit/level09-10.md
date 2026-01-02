# Bandit Level 9 → Level 10

## Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

## Solution
strings data.txt and you can optionally grep that output to find everything with ===

### Reconnaissance
This one i was able to run cat and find the flag towards the end. Going to try and use the commands they told us though.

### Commands Used
```
cat,grep,strings
```

### Explanation
strings allow you to see all the printable strings in a file, then I can grep that output to find all the ones with ==

## Flag
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

## What I Learned
- Strings command
- searching through printable strings
