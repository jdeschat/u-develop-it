# U-develop-it
[![npm](https://badge.fury.io/js/inquirer.svg)](http://badge.fury.io/js/inquirer)

## Description
This voting application performs the CRUD (creating, reading, updating, and deleting) operations on data about candidates, parties, and votes. The voting API exposes these operations to users via Express.js routes. MySQL Shell is used to connect to the MySQL server and create a database and a table. Then, in the MySQL Shell, we execute SQL commands to handle the CRUD operations.

![alt text](https://github.com/jdeschat/u-develop-it/blob/main/assets/img/u-develop-it.png)

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Tests](#tests)
- [Technology Used](#technology-used)
- [Questions](#questions)

## User Story
```
AS A U Develop it owner
I WANT back end functionality for my application
SO THAT I can launch a full-stack app for voting
```
## Installation

To install this application, clone the code into your terminal for the respective repository. Then, install npm by entering the command ```npm init```  into the terminal. Install express by entering ```npm i express``` into the command line. In the “package.json” file, be sure to change the “test” to “jest”, as such ```”test”: “jest”,```. Finally, the program can then be run by entering ```node server.js``` into the command line, and answering each question appropriately.

To launch the MySQL command-line client, enter the flowing command in a Command Prompt window: ```mysql -u root -p ```. The ```-p```option is needed only if a root password is defined for MySQL. Enter the password when prompted.

Create and populate a table with MySQL, for example:
1.	mysql> show databases;
2.	mysql> CREATE DATABASE animals_db;
3.	mysql> use animals_db;
4.	mysql> Create TABLE dogs(
a.	-> id INTEGER(11) AUTO_INCREMENT PRIMARY KEY,
b.	-> petName VARCHAR(100),
c.	-> petAge INTEGER(11)
d.	-> );
5.	mysql> show tables;
6.	mysql> INSERT INTO dogs(petName, petAge) VALUES (‘Sam’, 6)
a.	-> ;
7.	mysql> INSERT INTO dogs(petName, petAge) VALUES (‘Ginger’, 8)
a.	-> ;
8.	mysql> SELECT * FROM dogs;

## Usage
1. Install npm: npm init -y
2. Install express: npm i express
3. Open mysql in the command-line
4. Type in "SHOW DATABASES;" then "USE election;"
5. Then use the "SELECT * FROM" to select a table

## Contributors
To contribute to Professional-README-generator, clone this repo locally and commit your code on a separate branch.
  
Contributors:

<a href="https://github.com/jdeschat/u-develop-it/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jdeschat/u-develop-it" />
</a>

Made with [contributors-img](https://contrib.rocks).

## Tests
![GitHub license](https://img.shields.io/badge/test-100%25-success)

## Technology Used
- MySQL2
- Node.js
- Express.js
- Jest
- API

## Questions
My Github username is jdeschat, which can be accessed here https://github.com/jdeschat/u-develop-it.

The Github page for this project can be accessed using the following link: https://jdeschat.github.io/u-develop-it/.

You can reach me at jdeschat@gmail.com with additional questions.
