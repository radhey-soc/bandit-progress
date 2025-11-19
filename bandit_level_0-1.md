# Bandit Level 0 → 1

**Command used to connect:**
ssh bandit0@bandit.labs.overthewire.org -p 2220

**Command used to get the password:**
cat readme

**Reason it worked:**
The `ssh` command opened a remote terminal session using the correct username and port. Once connected, `cat readme` displayed the content of the file named `readme`, which contained the password for the next level.

