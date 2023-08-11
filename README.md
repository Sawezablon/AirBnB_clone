# 0x00. AirBnB clone - The console
![Alt text](image.png)

## Background Context

### First step: Write a command interpreter to manage your AirBnB objects.
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…
Each task is linked and will help you to:
    - put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
    - create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
    - create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
    - create the first abstracted storage engine of the project: File storage.
    - create all unittests to validate all our classes and storage engine

## What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:
    - Create a new object (ex: a new User or a new Place)
    - Retrieve an object from a file, a database etc…
    - Do operations on objects (count, compute stats, etc…)
    - Update attributes of an object
    - Destroy an object

## Resources
- cmd module
- cmd module in depth
- packages concept page
- uuid module
- datetime
- unittest module
- args/kwargs
- Python test cheatsheet
- cmd module wiki page
- python unittest

# Requirements

## Python Scripts
    - Allowed editors: vi, vim, emacs
    - All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
    - All your files should end with a new line
    - The first line of all your files should be exactly #!/usr/bin/python3
    - A README.md file, at the root of the folder of the project, is mandatory
    - Your code should use the pycodestyle (version 2.8.*)
    - All your files must be executable
    - The length of your files will be tested using wc
    - All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
    - All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
    - All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
    - A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

## 