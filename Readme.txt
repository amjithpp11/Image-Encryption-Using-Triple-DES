Aim :To develop a DES based encryption method to encrypt any kind of file.
AND ALSO CONVERTING TO STANDALONE SINGLE APPLICATION FOR WINDOWS, LINUX, MAC OS SEPERATELY.

FEATURES: - 

Password hashing - PBKDF2 used(I will welcome advanced modes)
Salting done
Hashing and salting password performed multiple times (>10,000)
Peppering not done as it increases load in server, faster method are welcome
Digital signature in form of SHA256 used
Documentation provided in code
CBC (Cipher block chaining used) - triple DES
Initialization vector for CBC is derived from the password hash itself.

Note:Don't use crypto or pycrypto anymore!

Make sure to uninstall all versions of crypto and pycrypto first, then install pycryptodome:

	pip3 uninstall crypto 
	pip3 uninstall pycrypto 
	pip3 install pycryptodome

Reference :This project is refered from divyanshukumar,mentions are regarded.