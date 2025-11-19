Bandit Level 0 → 1
goal says: password is in a file called readme in the home directory. Home directory means the default folder you reach after SSH login

1. logged in using SSH:
ssh bandit0@bandit.labs.overthewire.org -p 2220
2. since, im already in the home directory where the file is located, i used 'ls' to verify the file, then used cat readme to read its contents, 
3. the output was the password of the bandit1

key concept: basic file handling, ssh to login into the port, instructions mention a filename and a location, check if you're already in that location, use ls to list all the files, then map if the file exists as mentioned in the instructions, then use cat to read the file.
