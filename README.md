# E-commerce

## Purpose
THe purpose of the application is to organize data so that the retail store can view and update data while having specific parts of the data linked in different tables.


## Built With
* Sequelize
* MySql2
* express
* dotenv


## How it Works
![Screencastify E-commerce](https://github.com/jen2ags/E-commerce/blob/main/assets/videos/E-commerce%20walkthrough.webm)

## Screen Shot
![Screenshot code](https://github.com/jen2ags/E-commerce/blob/main/assets/images/Code%20screenshot.png)

![Screenshot Insomnia](https://github.com/jen2ags/E-commerce/blob/main/assets/images/Insomnia%20screenshot.png)

## Installation
To install this application, run the following commands in the terminal:
 * npm init
 * npm install express sequelize mysql2
 * npm install dotenv -save
    * Be sure to save your database, username, and password in the .env file and then make sure it is added to the .gitignore

## Usage
Run the following commands in order to schema, seed the data and start the application:
* mysql -u root -p
    * Enter your mysql password
* In mysql run: source db/schema.sql
* Quit mysql
* In the root directory run: 
    * node seeds
    * npm start
* In Insomnia, run the GET, POST, PUT, and DELETE commands


## Contribution
Made by Jennifer Jennings