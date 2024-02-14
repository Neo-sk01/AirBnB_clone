# AirBnB Clone Project 🏡

Welcome to our rendition of the AirBnB Clone - the console! This project is the first step towards building a full-stack web application that mimics the functionality of AirBnB. It lays the groundwork for a series of projects that will teach us the ins and outs of web development, from front-end to back-end, and everything in between.

## Overview 🌐

The AirBnB clone project is a multipart series that aims to guide us through the process of creating a complete web application. This first part focuses on the backend, particularly on creating a command-line interface to manage our application's data. The journey will cover:

- The creation of a parent class `BaseModel` to handle initialization, serialization, and deserialization of instances to come.
- A simple flow of serialization/deserialization: Instance -> Dictionary -> JSON string -> File.
- Develop classes used for AirBnB (User, State, City, Place, etc.) that inherit from `BaseModel`.
- The implementation of the storage engine of the project: File Storage.
- Write comprehensive unittests for reliability and stability of my application.


## Features 🎉

- **Command Interpreter**: Allows us to manage the AirBnB objects.
  - Create a new object (e.g., User, Place).
  - Retrieve an object from storage.
  - Perform operations on objects (count, compute stats).
  - Update attributes of an object.
  - Destroy an object.

- **Serialization/Deserialization**: Conversion between objects and a JSON file storage system.
- **File Storage**: Abstracted storage engine to persist objects to a file.
- **Unittests**: Comprehensive tests to validate all our classes and storage engine.

## Technologies Used 🛠️

-  Python 3.8.5
-  Pycodestyle (2.8.*)
-  JSON files

## Available Commands

- create
- show
- destroy
- all
- update
- quit
- help


## Installation and Usage



**HOW TO START THE COMMAND INTERPRETER**

**STEP 1**

- Start the command-line Interpreter, go to the directory of the project 
and run : ./console.py in your terminal

- this will bring the command prompt (hbnb)

 **YOU MAY NOW ENTER COMMANDS**

**STEP 2**

- Creating a new object: to create a new object use the 'create' command a classname 

**STEP 3**

- Showing an object: to display an object, you need a class name and its 'id'

(hbnb) > show User user_id

- replace the "user_id" with the actual 'id' of the User.

**STEP 4**

- Listing all objects

- If you want to list all the users just simply type : (hbnb)> all

**STEP 5**

- Updating objects: here's how to update an objects attribute:

(hbnb) > upadate User user_id email "neosekaleli@gmai.com"

**STEP 6** 

- here is how to destroy a user

(hbnb) destroy User user_id 

**STEP 7** 

- To quit the console 

(hbnb) quit


