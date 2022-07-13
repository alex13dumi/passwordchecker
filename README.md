# passwordchecker
Using pwnedpasswords.com API i managed to create a program that can check if your password has been pwned or not.
You can enter how many passwords you want when executing main.py.
Password were written in a file, for security reasons. It's easier to type some text in a file then delete it, than typing in terminal or command line because you can check the history of it.

White spaces will not be considered as passwords,neither TABS.
# Usage
**python main.py**

You can add text to passwords.txt and the program will evaluate them.
You have got an example in the uploaded passwords.txt file.

# Requirements
* requests 
* hashlib