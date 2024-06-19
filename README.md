# Database-Administration-Project-Redacted-Software-Version-
The program simplifies data management tasks for administrators by providing intuitive interfaces for editing, deleting, importing, exporting, and printing data without requiring prior SQL database knowledge.

## Overview
This Database Administration Project originated as a project to evaluate my ability in Python development after three months of learning Python. It is designed as a task-specific tool, with certain functionalities redacted to maintain privacy.

## Features
- Login Page: Secure access control for authorized users.
- Create New User Page: Functionality to add new users to the system.
- Import: Ability to import data into the database from external sources.
- Export: Feature to export database data to external files or formats.
- Print Preview and Print: Tools for previewing and printing database contents.
- Display Table from Database: Interface to view database tables with ease.
- Edit Row: Options to edit data within rows, including clearing all fields, resetting changes, and saving modifications.
- Add Row: Functionality to insert new rows into the database.
- Delete Row: Capability to remove rows from the database.
- Refresh Page: Option to refresh the page to reflect the latest data changes.

## Installation
To use this application (only in Linux), follow these steps:
1. Download the Application: Download Python file to your local machine.

2. Install Python: Ensure you have Python installed on your system. You can download and install Python from [python.org](https://www.python.org/downloads/).

3. Set Up Environment (Optional but Recommended): It's good practice to work within a virtual environment to isolate your project's dependencies. Here's how you can set up and activate a virtual environment:
Install virtualenv (if not already installed):
   pip install virtualenv
   
Create a virtual environment:
   virtualenv env

Activate the virtual environment (On Linux):
   source env/bin/activate

4. Install Required Libraries: Use `pip`, the Python package installer, to install the required libraries. Open a terminal or command prompt and run the following commands:
   pip install pymysql pandas sqlalchemy PyQt5 menu

5. Setup MySQL Database/Server: Ensure you have set up a MySQL database/server. Create the following tables:
- User Table: Contains columns: id, username, password.
     
6. Run the Program: Launch the application by running the Python script:
   python /path/to/DataAdminSoftware.py
   Alternatively, you can run the program from an IDE.

## Development Environment
- Operating System: Ubuntu 20.04
- Python Version: Python 3.8.10
- MySQL Version: MySQL 8.0.36

## Usage
The program simplifies data management tasks for administrators by providing intuitive interfaces for editing, deleting, importing, exporting, and printing data without requiring prior SQL database knowledge. Follow the steps below to use the application:
1. Set up MySQL Details: edit the detail inside the Python script.
dbhost= "your_host" 
dbusername="your_username"
dbpassword="your_password"
dbdatabase="your_database"  
The DataAdminSoftware.py can automatically generate input boxes based on the database table structure. 

2. Launch the Application: run the Python script to launch the program.
3. Login: Enter your credentials (username and password) to access the system. If you're a new user, click on the "Create New User" button to register.
4. Main Interface: Once logged in, you'll be presented with the main interface wiht menu(s) such as import, export, print, and table display.

### Example:
Suppose you want to edit a customer's information:
1. Log in to the system using your credentials.
2. Navigate to the customer database table.
3. Select the row corresponding to the customer whose information you want to edit.
4. Click on the "Edit" button and make the necessary changes.
5. Save your modifications.
