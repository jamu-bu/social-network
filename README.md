# social-network

**Week-18 Challenge (MongoDB)**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

## Table of Contents

- [Description](#description)
- [Live Screen Recording of Application Functionality](#live-screen-recording-of-application-functionality)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Credits](#credits)
- [Features](#features)
- [Usage Information](#usage-information)
- [Suggested Future Development](#suggested-future-development)
- [Contribution Guidelines](#contribution-guidelines)
- [Test Instructions](#test-instructions)
- [License](#license)
- [Questions](#questions)

## Description

This social network was created using node, express, js, mongodb, mongoose, and insomnia to test get, post, update, delete routes.

## Live Screen Recording of Application Functionality

## Technologies Used

- Node.js (v16.19.1)
- Express.js (v4.18.2)
- JavaScript
- MongoDB
- Mongoose (ODM)
- npm dependencies: express (v4.18.2), mongoose (v7.2.2)
- DevDependencies: nodemon (v2.0.22), Jest (v29.5.0)
- MongoDB Compass for database visualization
- Insomnia for testing API routes

## Installation

1. Initialize the project by running the following command in your terminal:
   ```
   npm init -y
   ```

2. Install the project's dependencies by running:
   ```
   npm install
   ```

   Install each dependency separately with these commands:
   - Express: `npm install express`
   - Mongoose: `npm install mongoose`
   - Nodemon: `npm install nodemon`
   - Jest: `npm install jest`

3. Ensure you have access to a MongoDB account and MongoDB Compass to interact with the database visually.

4. Once all dependencies are installed, you can start the server by running the following command in your terminal:
   ```
   npm start
   ```

   If you prefer to use nodemon for auto-refresh during development, you can run:
   ```
   npm run dev
   ```

5. You can test the API routes in Insomnia.

## Credits

- The project's general route structure and file organization were influenced by the Week-18 mini-challenge.
- Thank you to my tutor, Wen-Jui Cheng :D!

## Features

Key features of this application include:

- Creating users and thoughts
- Searching for users and thoughts
- Updating user and thought information
- Deleting users and thoughts
- Adding reactions to thoughts
- Creating and managing friend lists

Whenever a thought, reaction, or friend is added or removed in the database, the user object is updated accordingly.

## Usage Information

To use this application, follow these