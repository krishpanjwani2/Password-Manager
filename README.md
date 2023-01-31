# Password-Manager
In Python 
This password manager uses a simple text file to store the passwords, with each line in the file containing a website name, username, and password separated by commas. The user can choose to either store a password (which will be encrypted in a real-world scenario) or retrieve a password from the password file. The password retrieval feature uses the website name as a key to search for the password in the file. The password manager uses the getpass library to securely retrieve the password from the user without echoing it on the screen.
