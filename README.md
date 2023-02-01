# E-Commerce-ORM

- [E-Commerce-ORM](#e-commerce-orm)
  - [Description](#description)
  - [Technologies](#technologies)
  - [License](#license)
  - [Usage](#usage)
  - [Instructions](#instructions)
  - [Contribution](#contribution)
  - [Walk Through Video](#walk-through-video)


## Description 
This application is the back end of an e-commerce site. This is created using Express.js API and configured to use sequelize to interact with a MYSQL database. This application is not deployed, a demonstration of functionality can be found in the walkthrough video. The motivation behind its design is because of the popularity of the e-commerce industry and their platforms flexibility to help businesses of all sizes. Due to the prevalence of these platforms, developers are encouraged to understand the fundamental architecture of e-commerce sites and practice building applications to support them. 

This application contains the back-end logic for an e-commerce site:

## Technologies 
1. JavaScript
2. [MySQL2](https://www.npmjs.com/package/mysql2)
3. [Node.js](https://nodejs.org/en/)
4. [Express.js](https://www.npmjs.com/package/express)
5. [Dotenv](https://www.npmjs.com/package/dotenv)
6. [Sequelize](https://www.npmjs.com/package/sequelize)

## License 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Usage 
Designed for developers or small business owners. Prerequisite technologies include CLI, MySql server ( accountr & username information )

## Instructions
1. Clone the main project, then open the cloned file.
2. Make sure you are in the main project folder using the 'cd' command.
3. Open command prompt and run: npm install
4. Create a `.env` in the root directory
5. Create the following three variables in the `.env` file:
- `DB_NAME=ecommerce_db`
- `DB_USER=`[MySQL username]
- `DB_PW=`[MySQL password]
6. Open: `MySQL` CLI.
7. Run: `source db/schema.sql` to create the database.
8. Run: `npm run seeds` to seed the databse.
9. Run: `npm start`
## Contribution 
Created by Eileen Ma 

## Walk Through Video

