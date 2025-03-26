

<div align="center">
    <img src="https://github.com/tuzup/SplitApp/blob/master/client/public/static/logo.png?raw=true" alt="Logo" width="80" height="80">
  </a>

  <h2 align="center">SplitShare</h2>

  <p align="center">
    Build with the MERN stack (MongoDB, Express, React and NodeJS).
    <br />
    <br />
    <br />
  </p>
</div>

![SplitShare](https://github.com/ethicalADI/SplitShare/blob/main/images/UI.png)

## MERN Stack Group Expense Splitting Application

  * [Introduction](#introduction)
  * [Key Features](#key-features)
  * [Technologies used](#technologies-used)
      - [Frontend](#frontend)
      - [Backend](#backend)
      - [Database](#database)
  * [Configuration and Setup](#configuration-and-setup)


## Introduction
This is a full-stack expense-splitting app – a Splitwise clone built using the MERN stack (MongoDB, Express, React & Node.js), designed to split group expenses among friends. With SplitShare, users can add expenses, track shared payments, and access detailed analytics, including group balances, monthly spending, and category-wise expense graphs.

![Features](https://github.com/ethicalADI/SplitShare/blob/main/images/dashboard.png)

## Key Features
- Create user groups and track group expense 
- Keep track of shared expenses and settle your corresponding balances in a convenient and personalized way. 
- Get Analytical graphs to understand your expenditure trend 
- Multiple user registration.
- Authentication using JSON web token (JWT) 


## Technologies used
This project was created using the following technologies.

#### Frontend

- React JS
- Redux (for managing and centralizing application state)
- Axios (for making api calls)
- Material UI (for User Interface)
- Chart.js (To display various analytics graphs)
- React-chartjs-2  
- Gravitar (for user profile picture)

#### Backend

- Express
- Mongoose
- JWT (For authentication)
- bcryptjs (for data encryption)

#### Database
MongoDB (MongoDB Atlas)

## Configuration and Setup
In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine. 
- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the client on one terminal and the server on the other terminal)

In the first terminal - Setup Clinet 

```
$ cd client
$ npm install (to install client-side dependencies)
$ npm start (to start the client)
```

For setting up backend (root directory) 
- create a .env file in the root of your directory.
- Supply the following credentials

```
PORT=3001
MONGODB_URI=
ACCESS_TOKEN_SECRET=

```



Provide some random key in ACCESS_TOKEN_SECRET or you could generate one using node enter the below command in the terminal to genrate a random secret key 

```
node -e "console.log(require('crypto').randomBytes(256).toString('base64'));"
```

In the second terminal (*in the project root directory (back-end))

```
$ npm install (to install server-side dependencies)
& npm start (to start the server)
```

