# Tech-Blog

## Description

In this Project I created the back end and front end for a Tech Blog site. Which utilizes an MVC framework using MySQL, Express.js, Sequelize and handlebars.js in order to allow users to create secure accounts and perform appropriate CRUD operations allowed by the server.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Badges](#Badges)
- [Features](#Features)
- [Questions](#Questions)

## Installation

To Install:

Install node.js lts

Clone the repository from GitHub (https://github.com/ajsherrill2/Tech-Blog).

Run these command lines in your terminal to install necessary dependencies:

```
npm init -y
npm install
```

Additional installations (sequalize, mysql2, and dotenv)

```
npm i sequalize
npm i mysql2
npm i dotenv
npm i bcrypt
npm i connect-session-sequelize
npm i express
npm i express-handlebars
npm i express-session
```

Please Run "SOURCE db/schema.sql;" atleast once in your MySQL terminal.

```
mysql -u root -p
-SOURCE db/schema.sql;
```

Please change ".env.EXAMPLE" to ".env" and provide personal DB_PASSWORD, DB_NAME, DB_USER and DB_SESS.

## Usage

Direct your terminal to the repository root directory and run this command line to initiate application:

```
npm seed
```

Then

```
npm start
```

Direct your browser to "http://localhost:3001/"

Terminal demonstration [here](https://drive.google.com/file/d/1o_1B3Wm5yMKbVNdGeqd1olr6vcAP7isy/view)

Watch this short video demonstration [here](https://drive.google.com/file/d/1jTKvxYJ2jOR8X63Vfr8y7f1uv_X20_KL/view)

## License

This application is covered under the MIT license.

## Badges

![license](https://img.shields.io/badge/license-MIT-yellow.svg)

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

![badmath](https://img.shields.io/github/repo-size/ajsherrill2/Tech-Blog)

## Features

Features you will find in this app include:

- Previous posts in the database are viewable as well as the author and date it was created
- The user can Login and Signup to create posts after a period of time the user is logged out and will need to log back in to access dashboard and create comment priviledges
- Posts made by the current author can be edited and/or deleted

## Questions

If you have any questions about the repo open an issue or contact me directly at adamsherrill2@gmail.com. You can find more of my work at [ajsherrill2](https://github.com/ajsherrill2/).