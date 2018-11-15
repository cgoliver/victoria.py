# File System

Information in computers is stored in two ways: files and CPU memory. 

All pictures, documents, programs (excel, chrome, skype) are files that live on your computer's disk.

We can put files inside folders (aka directorys) as well as other folders.

The 'file system' is organized in a tree structure with one folder containing all folders in the computer, we call this folder the 'root' in UNIX systems (MAC, Linux) we give it the name `/`.

A *path* is a sequence of folders that go from root to a given folder.

This is the path from my root folder to this folder that contains notes:

	/Users/carlos/Projects/Victoria_Codes/Notes

And if I want to write the path to a specific file I just add it to the end of the path.

	/Users/carlos/Projects/Victoria_Codes/Notes/fist_class.md

Programs you often use are also files which are often stored in the Applications folder. For example

	/Applications/Skype.app

Is the Skype program file which contains instructions for the functionality of skype.


# BASH

Normally, you interact with your computer though what we call a GUI (Graphical User Interface). GUIs can be convenient because they are very easy to start using. The downside is that it is often difficult to automate processes and do things quickly. Since we want to learn how to program, it is important that we learn how to interact with our operating system in an efficient manner.

For this, we use the 'true' operating system which is a programming language and a set of associated applications that are very useful for interacting with the operating system, aka BASH.


Useful BASH commands:

	ls
	cd
	pwd
	mkdir
	rm

# Python

$ python 

We get the python interpreter which is a program that understands instructions in the language Python.

	2 + 2 
	4

We can get out of the python interpreter by hitting CTRL+D

# How to make a folder

$ mkdir [name of folder]


## Executing a python file

$ python name_of_file.py

