EXERCISES
Before you move on to Chapter 3, try out the skills you learned from this chapter by
completing the following exercises:


1. Navigate to /usr/share/wordlists/metasploit. This is a directory of multiple
wordlists that can be used to brute force passwords in various password-
protected devices using Metasploit, the most popular pentesting and
hacking framework.

Answer: cd /usr/share/wordlists/metasploit

2. Use the catcommand to view the contents of the file passwords.lst.

Answer: cat passwords.lst

3. Use the morecommand to display the file passwords.lst.

Answer: more passwords.lst


4. Use the lesscommand to view the file passwords.lst.

Answewr: less password.lst


5. Now use the nlcommand to place line numbers on the passwords in
passwords.lst. There should be 88,396 passwords.

Answer: nl password.lst


6. Use the tailcommand to see the last 20 passwords in passwords.lst.

Answer: tail -20 password.lst



7. Use the catcommand to display passwords.lst and pipe it to find all the
passwords that contain 123.

Answer: cat password.lst | grep 123