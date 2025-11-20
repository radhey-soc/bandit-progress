Bandit Level 1 → Level 2
Level Goal says: The password for the next level is stored in a file called - located in the home directory.

Logged in as bandit1 using SSH:
ssh bandit1@bandit.labs.overthewire.org -p 2220

After login, I am already in the home directory.

Used ls to verify the file named -.

The shell treats - as an option, not a filename. To force it to treat it as a file, I had to specify the path using ./-.

Used cat ./- to read the file.

The output was the password for bandit2.
