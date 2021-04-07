# Budget-Tracker

# Table of Contents
1. [Project Description](#description)
2. [Usage](#usage)
3. [UI](#ui)
4. [Technology](#technology)
5. [Github](#github)

## Project Description <a name="description"></a>
This Progressive Web Application was designed so the user can track their income/spending in order to budget their funds.  Each transaction is stored in the MongoDB database and is rendered on the table/chart.  A key functionality is the use of IndexedDB as well as Manifest and Service Worker for the app to work offline as well.

## Usage <a name="usage"></a>
- Deployed to Heroku: [Budget Tracker](https://agile-spire-71979.herokuapp.com/)
- If running on local computer:\
From the command line,\
'npm i'\
'npm run start'\
In the browser: localhost:3000

## UI <a name="ui"></a>
![screenshot1](/images/budgetSS.jpeg)

## Technology <a name="technology"></a>
This PWA was created with Node.js and utilizes MongoDB as a database.  For offline data storage, IndexedDB, Manifest, and Service Worker via Chrome Devtools are used.  In the development process Atlas was used to connect to cloud and Heroku for deployment.  The application requires the following npm packages:
- express
- mongoose
- morgan
- compression
- lite-server

## Github <a name="github"></a>
Shauna Dunn\
Github username: [sleepytomatoes](https://github.com/sleepytomatoes)\
Email: shaunadunn1@gmail.com