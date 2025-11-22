Bandit Level 4 → Level 5
Level Goal says: The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

Steps:
1. Logged in as Bandit4 using SSH: 
ssh bandit4@bandit.labs.overthewire.org -p 2220

2. Landed in inhere directory using cd which refers to change directory:
cd inhere

3. Used file command to idenitfy the type of every file in the current directory (inhere):
file ./* 
file → identify the real type of a file (content-based).
./ → current directory.
* → all items inside it.

4. ./-file07 identified as the only human-readable file in the inhere directory.

5. Read ./-file07 using cat:
cat ./"-file07"
./ tells the shell it's a file in the current directory, not a flag.
The output was the password for Bandit5.
