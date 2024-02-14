# AirBnB Clone Project 🏡

Welcome to our rendition of the AirBnB Clone - the console! This project is the first step towards building a full-stack web application that mimics the functionality of AirBnB. It lays the groundwork for a series of projects that will teach us the ins and outs of web development, from front-end to back-end, and everything in between.

## Overview 🌐

The AirBnB clone project is a multipart series that aims to guide us through the process of creating a complete web application. This first part focuses on the backend, particularly on creating a command-line interface to manage our application's data. The journey will cover:

- The creation of a parent class (`BaseModel`) to handle initialization, serialization, and deserialization of future instances.
- A simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> File.
- Development of the classes used for AirBnB (User, State, City, Place, etc.) that inherit from `BaseModel`.
- The implementation of the first abstracted storage engine of the project: File Storage.
- Writing comprehensive unittests to ensure reliability and stability of our application.

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

- **Language**: Python 3.8.5
- **Style guide**: Pycodestyle (2.8.*)
- **Storage**: JSON files

## Installation and Usage 🔧

Clone the repository to your local machine:

```bash
git clone https://github.com/your_github_username/your_repository_name.git

