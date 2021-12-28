# Budget Tracker

- A budget tracking application that allows both online and offline access and functionality.
- The application uses NodeJS, Express, MongoDB, Mongoose, etc. to allow users to input values and explore the additions and subtractions in their budget.

## User Story

```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```

## Project Criteria

```
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```

## Deployed Website Link

https://sleepy-cove-34074.herokuapp.com/

## Technologies

- JavaScript
- NodeJS
- Express
- MongoDB
- Mongoose
- Progressive Web App (PWA)
- Service Workers
- Indexed DB
- Web App Manifest

## Installation

- Please use the link above to view the deployed website, otherwise:
- Please clone the GitHub repository to your local computer, etc.
- Please do an `npm install` **(and `npm init -y` in case package.json is missing)**
- Ensure Mongoose and Express are installed
- Start the server by running `npm start`
- Please change ports on the server.js in case PORT 3001 is in use
