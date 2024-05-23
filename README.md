# Bash DBMS Project

## Overview

This project is a Bash Shell Script Database Management System (DBMS) that enables users to store and retrieve data from the hard disk. The application is a command-line interface (CLI) menu-based app that provides users with various database management functionalities.

## Features

### Main Menu:
- **Create Database:** Allows the user to create a new database.
- **List Databases:** Displays a list of all existing databases.
- **Connect To Database:** Connects the user to a specific database.
- **Drop Database:** Deletes an existing database.

### Database Menu (upon connection to a specific database):
- **Create Table:** Allows the user to create a new table in the connected database.
- **List Tables:** Displays a list of all tables in the connected database.
- **Drop Table:** Deletes a specific table from the connected database.
- **Insert into Table:** Inserts a new record into a specified table.
- **Select From Table:** Retrieves and displays records from a specified table.
- **Delete From Table:** Deletes records from a specified table based on a condition.
- **Update Table:** Updates records in a specified table based on a condition.

## Getting Started

### Prerequisites

- A Unix-like operating system (Linux, macOS, etc.)
- Bash shell

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yassa3/Bash_DBMS_Project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bash-dbms-project
    ```
3. Make the main script executable:
    ```bash
    chmod +x dbms.sh
    ```

### Usage

1. Run the main script:
    ```bash
    ./dbms.sh
    ```
2. Follow the on-screen menu to perform various database operations.

### Main Menu

- **Create Database:** Enter the name of the new database when prompted.
- **List Databases:** View the names of all databases.
- **Connect To Database:** Enter the name of the database to connect to.
- **Drop Database:** Enter the name of the database to delete.

### Database Menu

- **Create Table:** Specify the table name and its schema (column names and types).
- **List Tables:** View the names of all tables in the current database.
- **Drop Table:** Enter the name of the table to delete.
- **Insert into Table:** Enter the values to insert into the specified table.
- **Select From Table:** Enter the query to retrieve records from the table.
- **Delete From Table:** Specify the condition to delete records from the table.
- **Update Table:** Specify the condition and new values to update records in the table.

## Example

```bash
./dbms.sh

# Main Menu
1. Create Database
2. List Databases
3. Connect To Database
4. Drop Database
5. Exit
Choose an option: 1
Enter database name: example_db

# Database Menu (connected to example_db)
1. Create Table
2. List Tables
3. Drop Table
4. Insert into Table
5. Select From Table
6. Delete From Table
7. Update Table
8. Back to Main Menu
Choose an option: 1
Enter table name: users
Enter columns (e.g., id INT, name TEXT): id INT, name TEXT
