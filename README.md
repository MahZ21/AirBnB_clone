Airbnb clone
The console is the first segment of the AirBnB project at Holberton School that will collectively cover fundamental concepts of higher level programming. The goal of AirBnB project is to eventually deploy our server a simple copy of the AirBnB Website(HBnB). A command interpreter is created in this segment to manage objects for the AirBnB(HBnB) website.

Functionalities of this command interpreter:
Create a new object
Retrieve an object from a file
Do operations on objects
Update attributes of an object
Destroy an object
Table of Content
Environment
File Descriptions
Usage
Examples of use
Bugs
Authors
License
Environment
This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3)

Installation
Clone this repository: `git clone "https://github.com/MahZ21"
Access AirBnb directory: cd AirBnB_clone
Run hbnb(interactively): ./console and enter command
Run hbnb(non-interactively): echo "<command>" | ./console.py
File Descriptions
console.py - the console contains the entry point of the command interpreter. List of commands this console current supports:

EOF - exits console
quit - exits console
create - Creates a new instance ofBaseModel, saves it (to the JSON file) and prints the id
destroy - Deletes an instance based on the class name and id (save the change into the JSON file).
all - Prints all string representation of all instances based or not on the class name.
Examples of use
vagrantAirBnB_clone$./console.py (hbnb) help

Documented commands (type help ):
EOF all create destroy help quit show update

Bugs
No known bugs at this time.

Authors
Mahlet Zerihun Github || Gmail
License
Public Domain. No copy write protection.
