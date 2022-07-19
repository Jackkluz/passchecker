# Passchecker
A program to check the security of personal passwords.
Passwords are encrypted with a SHA1 hash and then only the first 5 values of the hash are sent to the API. The results are filtered to match the exact hash on the backend to avoid leaking the full hash of all the passwords you use to the API.

HOW-TO:
- Install requests using: pip install requests     (or read the documentation)
- Please enter your desired passwords to check into the passcheck.txt file and store in the PWD.
- Type passwords as exactly written and separate all passwords via a new line.
- Save the file and then run the program. Change passwords as necessary.
- Delete passwords from the passcheck.txt file when finished.
