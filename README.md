# Groupo
# Project 7 - Groupomania
Project Groupomania - Openclassrooms.
> Enterprise Social Network designed for Openclassrooms web developer training.
## Installation
First time, create your database MySQL

CREATE DATABASE groupomania;


Remember to check and/or configure the .env file :

MY_PORT = 8080          // Port used for back server.

// All informations for connect to database.
DB_DIAL = mysql         // Dial for database.
DB_NAME = groupomania   // Database name.
DB_USER = root          // Database username.
DB_PASS = admin         // Database password.
DB_HOST = localhost     // Database host.
DB_PORT = 3306          // Database port.


Install all the dependencies with npm.\
In the `back` directory :
bash
npm install
npm start

In the `front` directory :
bash
npm install
npm start


## Specificities
1. The first registered user will get administrator rights.
> It is not possible to remove administrator rights from the first user.
2. Only the administrator can permanently delete an account. For others, the account is deactivated and keeps articles, comments and user email address.
Administrateur
AdminAll
Admin1@gmail.com
password  : Admin1




## Features
* Signup / Login.
* Post article with/without image.
* Modify article/image.
* Delete article/image.
* Like/Unlike article.
* Post comment in article.
* Modify comment.
* Delete comment.
* Edit profile. (Firstname, Lastname, Email, Password, Avatar)
* Delete account.
* Logout.

## Groupomania Front-End
!javascript
!React
### Dependencies
* Axios (used for send request `GET`,`POST`,`PUT`,`DELETE`)
* jwt-decode (used for decode token in front)
### Available Scripts
In the `front` directory, you can run:

`npm start`\
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

`npm run build`\
Builds the app for production to the `build` folder.

## Groupomania Back-End
!javascript
!NodeJs
!Express.js

### Dependencies
* bcrypt (used to encrypt the user's password)
* dotenv (user for the management of environment variables)
* express (MVC-like framework)
* jsonwebtoken (used to secure connections with a token)
* multer (used for upload image/avatar)
* mysql/mysql2 (used for mysql database)
* sequelize (used to manage the database)
### Available Scripts
In the `back` directory, you can run:

`npm start`\
Runs the app server.

`npm run dev`\
Runs the app server in the development mode. (nodemon)

## Preview
!Login
!Sign
!Home
