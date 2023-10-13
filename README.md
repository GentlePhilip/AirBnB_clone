   PROJECT TITLE
AirBnB clone - The console

This group project is made up of the following:

# 0x00 Table of contents

# 0x01 Introduction

# 0x02 Environment

# 0x03 Installation

# 0x04 Experimentation

# 0x05 Usage

# 0x06 Authors

 # 0x01 INTRODUCTION
The AirBnB clone project is a team project that seems to develop a Python3 console that emulates the AirBnb object management.Create, update, destroy, save, and persist objects to a file (JSON file) using the console or command interpreter. This console will serve as a device for testing this storage engine.

 # 0x02 ENVIRONMENT
Python suite CRM terminal Github's distributed version control system, Suite CRM

The pycodestyle (version 2.7.*) style guidelines PEP-8 Using Python 3.8.3, the development and testing were conducted on an Ubuntu 20.04 LTS operating system. The editors that were utilised were Atom 1.58.0, VSCode 1.6.1, and VIM 8.1.2269. Manage the version with Git 2.25.1.

 # 0x03 INSTALLATION

git clone https://github.com/GentlePhilip/AirBnB_clone.git change to the AirBnb directory and run the command:

./console.py Execution In interactive mode

$ ./console.py (hbnb) help

# Documented commands (type help )
EOF help quit

(hbnb) (hbnb) (hbnb) quit $

in Non-interactive mode

$ echo "help" | ./console.py (hbnb)

# EOF help quit (hbnb) $ $ cat test_help help $ $ cat test_help | ./console.py (hbnb)

 # 0x04 EXPERIMENTATION &  0X05 USAGE
Documentation:The below are seen in the experimentation/testin folders
Modules: python3 -c 'print(import("my_module").doc)' Classes: python3 -c 'print(import("my_module").MyClass.doc)' Functions (inside and outside a class): python3 -c 'print(import("my_module").my_function.doc)' and

python3 -c 'print(import("my_module").MyClass.my_function.doc)' Python Unit Tests unittest module File extension .py Files and folders star with test_ Organization:for models/base.py, unit tests in: tests/test_models/test_base.py Execution command: python3 -m unittest discover tests or: python3 -m unittest tests/test_models/test_base.py run test in interactive mode echo "python3 -m unittest discover tests" | bash run test in non-interactive mode To run the tests in non-interactive mode, and discover all the test, you can use the command:
EOF all count create destroy help quit show update

(hbnb) Quit the console: (hbnb) quit $ Commands The commands are displayed in the following format Command / usage / example with output


 # 0x06 AUTHORS

# Nyarko Philip Abel aphilipnyarko@gmail.com

# Olekwa John johnolekwa@gmail.com 
