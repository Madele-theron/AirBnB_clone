# The AirBnB Clone Project - Console

![AirBnB Logo](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221124%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221124T145736Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=6ee3c632519230a4c57542df4a41be2449272ce3ba4c11cbb3e202c916b0de27)

## Project Description

This part of the AirBnB Project is dedicated to creating the backend.
Using the cmd module in Python to create a command interpreter.

## Description of the Command Interpreter:

It is similar to the Bash Shell, but it is limited to the specific use-case of the AirBnB Clone.

The command interpreter will serve as the frontend of this web app, where the user will be able to interact with the backend / database.

As part of the implementation of the command line interpreter coupled with the backend and file storage system, the folowing actions can be performed:

- Creating new objects (ex: a new User or a new Place)
- Retrieving an object from a file, a database etc…
- Doing operations on objects (count, compute stats, etc…)
- Updating attributes of an object
- Destroying an object

## How to start

## Installing

## How to use it

It can work in two different modes:

**Interactive** and **Non-interactive**.
Your shell should work like this in **interactive mode**:

```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

But also in **non-interactive mode**: (like the Shell project in C)

```
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
```

## Examples

## Authors

Madele Theron | [Email](mailto:madele.theron@gmail.com?subject=The%20AirBnB%20Clone%20Project) | [Gtihub](https://github.com/Madele-theron)
