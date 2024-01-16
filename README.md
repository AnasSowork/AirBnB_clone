# AirBnB Clone - Console

## Project Goal

The objective of this project is to deploy a simplified version of the AirBnB website on a server. While it doesn't encompass all features, it focuses on implementing key concepts of the higher-level programming track.

## First Step: Command Interpreter

The primary task is to develop a command interpreter to manage AirBnB objects. This step is crucial as it forms the foundation for subsequent projects.

## What's a Command Interpreter?

Similar to the Shell but tailored for a specific use-case. In this instance, it enables the management of project objects, allowing operations like creating, retrieving, updating, and destroying objects.

## Execution

The console operates interactively and non-interactively, akin to the Shell project in C.

### Interactive Mode:

bashCopy code

`$ ./console.py (hbnb) help`

### Non-Interactive Mode:

bashCopy code

`$ echo "help" | ./console.py (hbnb)`

## Commands

- create - Create an object
- show - Show an object based on ID
- destroy - Destroy an object
- all - Show all objects, by type or all types
- update - Update an instance based on class name and ID
- quit/EOF - Quit the console
- help - See descriptions of commands

## Getting Started

To start the console, use the following command in the shell:

bashCopy code

`AirBnB_clone$ ./console.py (hbnb)`

## Usage Examples:

### Create

bashCopy code

`(hbnb) create BaseModel`

### Show

bashCopy code

`(hbnb) show BaseModel 1234-1234-1234.`

### Destroy

bashCopy code

`(hbnb) destroy BaseModel 1234-1234-1234.`

### All

bashCopy code

`(hbnb) all or all State`

### Update

bashCopy code

`(hbnb) update BaseModel 1234-1234-1234 email "aibnb@holbertonschool.com"`

### Quit

bashCopy code

`quit or EOF`

### Help

bashCopy code

`(hbnb) help or help quit Defines quit option (hbnb)`

## Supported Classes

- BaseModel
- User
- State
- City
- Amenity
- Place
- Review

## Authors

- 01 Anas Falaki
- 02 Jalal Eddine Hafdi
