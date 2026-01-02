# Bandit Level 0 → Level 1

## Goal
The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220.
The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

## Solution
ssh -p 2220 bandit0@bandit.labs.overthewire.org
password: bandit0
List everything using ls once you log in, and cat the contents of the readme 

### Reconnaissance
My first try I did ssh -p 2220 bandit.labs.overthewire.org, I partially knew I might have to use bandit0@, but it didn't hurt to try and see. Then from previous Linux experience, I added the port to log into using -p and the username using [USER]@hostname

### Commands Used
```
ssh,ls,cat
```

### Explanation
This is the proper way to ssh into a host on a specific port using a username. Use -p to specify the port number, and [USER]@ before the host name

## Flag
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## What I Learned
Every detail counts while using CLI, the computer does it exactly what you tell it to.
