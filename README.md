# AirBnB clone - The console

## **Background Context**

## **First step: Write a command interpreter to manage your AirBnB objects.**

This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS template, database storage, API, front-end integration…

Each task is linked and will help you to:

- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
- create the first abstracted storage engine of the project: File storage.
- create all unittests to validate all our classes and storage engine

## **What’s a command interpreter?**

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

## **Resources**

Read or watch: [cmd module](https://intranet.hbtn.io/rltoken/Fx9HXIjmGzbmET4ylYg2Rw), [packages](https://intranet.hbtn.io/rltoken/jKl9WFpKA-fPt7_guv9_3Q), [uuid module](https://intranet.hbtn.io/rltoken/eaQ6aELbdqb0WmPddhD00g), [datetime](https://intranet.hbtn.io/rltoken/_ySDcgtfrwLkTyQzYHTH0Q), [unittest module](https://intranet.hbtn.io/rltoken/QX7d4D__xhOJIGIWZBp39g), [args/kwargs](https://intranet.hbtn.io/rltoken/jQd3P_uSO0FeU6jlN-z5mg), [Python test cheatsheet](https://intranet.hbtn.io/rltoken/WPlydsqB0PG0uVcixemv9A)

### **Requirements Python Scripts**

- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
- All your files should end with a new line
- The first line of all your files should be exactly #!/usr/bin/python3
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the PEP 8 style (version 1.7 or more)
- All your files must be executable
- The length of your files will be tested using wc
- All your modules should have a documentation (python3 -c 'print(**import**("my_module").**doc**)')
- All your classes should have a documentation (python3 -c 'print(**import**("my_module").MyClass.**doc**)')
- All your functions (inside and outside a class) should have a documentation (python3 -c 'print(**import**("my_module").my_function.**doc**)' and python3 -c 'print(**import**("my_module").-MyClass.my_function.**doc**)')

### **Requirements Python Unit Tests**

- Allowed editors: vi, vim, emacs
- All your files should end with a new line
- All your test files should be inside a folder tests
- You have to use the unittest module
- All your test files should be python files (extension: .py)
- All your test files and folders should start by test_
- Your file organization in the tests folder should be the same as your project
e.g., For models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py
e.g., For models/user.py, unit tests must be in: tests/test_models/test_user.py
- All your tests should be executed by using this command: python3 -m unittest discover tests
- You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py
- All your modules should have a documentation (python3 -c 'print(**import**("my_module").**doc**)')
- All your classes should have a documentation (python3 -c 'print(**import**("my_module").MyClass.**doc**)')
- All your functions (inside and outside a class) should have a documentation (python3 -c 'print(**import**("my_module").my_function.**doc**)' and python3 -c 'print(**import**("my_module").MyClass.my_function.**doc**)')
- We strongly encourage you to work together on test cases, so that you don’t miss any edge case

 HOW THE CONSOLE WORKS

## Steps for testing the console

### 1. Clone the repository with HTTPS

```bash
git clone https://github.com/Roymaniac/AirBnB_clone.git
```

### 2. Go to folder AirBnB_clone

```bash
cd AirBnB_clone
```

### 3. Run the consol file

```bash
./console.py
```

After in you screen can show the prompt of the terminal:

```bash
(hbnb)
```

## Command for test the console

the command that you can type are:

- help ó ?: this show the help available for command and the commands.

```bash
(hbnb)?

Documented commands (type help <topic>):
========================================
EOF  all  create  destroy  help  quit  show  update

(hbnb)help

Documented commands (type help <topic>):
========================================
EOF  all  create  destroy  help  quit  show  update

(hbnb)
```

- **EOF** and **quit**: this commands are for exit the console, the EOF is the signal get to press the key combination Ctrl + d

```bash
(hbnb)quit
# AirBnB_clone
