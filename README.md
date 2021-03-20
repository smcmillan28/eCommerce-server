# Back-End Ecommerce Server

## Description of Project
This project is a back-end, Node.js application that uses the npm sequelize and express packages to display and edit a product database using CRUD routes.   

Usage instructions and video demo are below, but once initiated, you will have the option to view, update, post, and delete data and/or edit information in the database.  In order to do so, you will need to open Postman or Insomnia Core to initiate connection with the server and send requests.

Read below for further details.  Enjoy!

## Table of Contents

- [Usage](#usage)
- [Credits and Code Used](#credits-and-code-used)
- [Application Demo](#application-demo)
- [Questions](#questions)
- [Takeaways and Future Development](#takeaways-and-future-development)

## Usage
To run the program, type the following command(s) in your terminal:

Package Installations

```bash
npm install sequelize
npm install express
npm install mysql
```

Database Setup
- You will need to either run schema file through your MySQL CLI or copy/paste the db/schema.sql file directly into your workbench.
- Then, you will need to run the seeds file as below:

```bash
node seeds/index.js
```

Server Connection

```bash
npm start
```

## Credits and Code Used

- JavaScript/ES6
- Node.js
- SQL/Sequelize
- npm sequelize and express packages
- Postman

## Application Demo

Please click [here](https://drive.google.com/file/d/11f_B_uUn0dUkRaqfAaBjMIJ_C5O0I23J/view) for a video walkthrough!

## Questions
Check out my GitHub profile [here.](https://github.com/smcmillan28)

Feel free to send me an email, as well: smcmillan1991@gmail.com

## Takeaways and Future Development
Venturing away from direct SQL queries, this application uses the sequelize ORM package to allow for more dynamic database interaction through the use of classes and express routes.  Future development items include: 

- Delete category route updates
- Adding a front-end view to allow users to interact outside of Postman