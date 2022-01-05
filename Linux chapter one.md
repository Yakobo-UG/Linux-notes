LINUX EXERCISE 1:

Before you move on to Chapter 2, try out the skills you learned from this
chapter by completing the following exercises:

1. Use the lscommand from the root (/) directory to explore the
directory structure of Linux. Move to each of the directories with
the cdcommand and run pwdto verify where you are in the directory
structure.

Answer: commands used: ls, cd and pwd


2. Use the whoamicommand to verify which user you are logged in as.

Answer: whoami

3. Use the locatecommand to find wordlists that can be used for
password cracking.

Answer: locate password | grep wordlist

4. Use the catcommand to create a new file and then append to that
file. Keep in mind that >redirects input to a file and >>appends to a
file.

Answer: cat > newfile
	cat >> newfile


5. Create a new directory called hackerdirectory and create a new file in
that directory named hackedfile. Now copy that file to your /root
directory and rename it secretfile.

Answer: mkdir hackerdirectory 
	cd hackerdirectory
	cp hackerdirectory /hackertdirectory/root