Bandit Level 3 → Level 4
Level Goal says: The password for the next level is stored in a hidden file in the inhere directory.

Steps: 
1. Logged in as bandit3 using SSH:
ssh bandit3@bandit.labs.overthewire.org -p 2220

2. Landed in inhere directory using cd which refers to change directory.
cd inhere

3. Used ls to display the files + hidden ones:
ls -la
l in la shows detailed information for each file — permissions, number of links, owner, group, size, modification date, and file name.
a in la means all files, including hidden ones.

4. Hidden file found as "...Hiding-From-You"

5. Read the hidden file using cat:
cat ./"...Hiding-From-You"

6. The output was the password for bandit4.
