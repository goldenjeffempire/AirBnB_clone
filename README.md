# 0x00. AirBnB clone - The console

## Project Description

The goal of the project is to deploy on a server a simple copy of the AirBnB website. It won’t implement all the features, only some of them to cover all fundamental concepts of the higher level programming track. 

## First step: Write a command interpreter to manage your AirBnB objects.

This is the first step towards building your very own AirBnB clone web application. It's crucial because everything you create in this project will be used in all the other parts of your application like HTML/CSS templates, storing data in a database, setting up an API, and integrating the front-end.

## What’s a command interpreter?

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

 . Create a new object (ex: a new User or a new Place)
 . Retrieve an object from a file, a database etc…
 . Do operations on objects (count, compute stats, etc…)
 . Update attributes of an object
 . Destroy an object

## Execution

Your shell should work like this in interactive mode:

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
