Bandit Level 0 → 1
Level Goal says: Password is in a file called readme in the home directory. Home directory means the default folder you reach after SSH login

Steps:
1. Logged in using SSH:
ssh bandit0@bandit.labs.overthewire.org -p 2220

2. Already landed in the home directory where the file is located, used 'ls' to verify the file, used cat readme to read its contents.

3. The output was the password of the bandit1.

Key concept: Basic file handling, SSH to login into the port, instructions mention a filename and a location, check if you're already in that location, use ls to list all the files, then map if the file exists as mentioned in the instructions, then use cat to read the file.
