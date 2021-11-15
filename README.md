# MySQL-Employee-Tracker

MySQL-Employee-Tracker is an interface command program that make it easy for non-developers to view and interact with information stored in databases. This interface is a good example of a Content Management Systems; a command line application for managing a company's employees using node, inquirer, and MySQL.


## User Story
As a business owner
I want to be able to view and manage the departments, roles, and employees in my company
So that I can organize and plan my business

## Design
This application follows the database shcema containing three variables:

![image](https://user-images.githubusercontent.com/87583026/141704860-f4af1c79-867b-4f58-81d9-d6005907f4e6.png)

## About

Application tree structure: The application is user friendly and built to handle large amount of data (ie: what if the company have about 10,000 employees and 1,000+ roles)

* View All Employees - command that prints all employees in a table. Table contains employee id, employee name, title, department, salary and employee manager.

* View All Employees By Manager - command that prints all employee managers and their associates.

* View All Employees By Department - command that prints all departments and the employee under it.

* View All Roles - command that prints all roles/ title and the corresponding employee.

* Add An Employee - command line that adds a new entry to the database.

* Remove An Employee - command line that deletes an employee from the database

* Update Employee Role - command line that updates the role/ title of an employee.

## Install
* npm i - to install all file in order for npm to work
* npm i inquirer - to use inquirer (to interact with the user via command line)
* npm init - to create a json file
* npm i mysql - to connect to MySql database
* npm console.table - to format tables

## Run 
* node index.js

## Dependencies
![image](https://user-images.githubusercontent.com/87583026/141707299-92e85f10-bae5-4cac-a930-5c053ecd70c7.png)

## Built with
* JavaScript
* jQuery
* ES6+
* Node.js
* MySQL2
* Inquirer

