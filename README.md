# E-Commerce Backend

## Description

The backend for an e-commerce site. The application uses an Express.js API and the Sequelize ORM (Obect Relational Mapping) library to interact with a MySQL database.

## Built With

- JavaScript
- Node.js
- Express.js
- MySQL2
- Sequelize
- dotenv

## Installation

1. Clone the repo using `git clone`.
2. Navigate to the app directory.
3. Run `npm install` to install dependencies.
4. Input your MySQL username and password into the .env file.
5. Create the schema from the MySQL shell by running the following commands in the terminal:
   - `MySQL -u root -p`
   - Enter your MySQL password when prompted.
   - `source db/schema.sql`
   - `quit`
6. Seed the database from the command line:
   - `node seeds/index.js`
7. Run `npm start` in the command line to launch the application.

## Usage

Link to video demonstration: [E-Commerce Backend Demo](https://drive.google.com/file/d/1wd2QI5SIx1ZIppNveC4BGXRGYnqWvMdT/view)

![Video demonstration of how to use the app](assets/images/e-commerce-backend-demo.gif)

## Contribution

Made with ❤️ by Kelsey Alderman
