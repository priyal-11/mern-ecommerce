# MERN Ecommerce

## Description

An ecommerce store built with MERN stack, and utilizes third party API's. This ecommerce store enable three main different flows or implementations:

1.  Buyers browse the store categories, products and brands
2.  Sellers or Merchants manage their own brand component
3.  Admins manage and control the entire store components

### Features:

*   Node provides the backend environment for this application
*   Express middleware is used to handle requests, routes
*   Mongoose schemas to model the application data
*   React for displaying UI components
*   Redux to manage application's state
*   Redux Thunk middleware to handle asynchronous redux actions

## Docker Guide

To run this project locally you can use docker compose provided in the repository. Here is a guide on how to run this project locally using docker compose.

Clone the repository
```
git clone [YOUR_REPOSITORY_URL]
```

Edit the dockercompose.yml file and update the the values for MONGO_URI and JWT_SECRET

Then simply start the docker compose:

```
docker-compose build
docker-compose up
```

## Database Seed

*   The seed command will create an admin user in the database
*   The email and password are passed with the command as arguments
*   Like below command, replace brackets with email and password.

```
npm run seed:db [email-***@****.com] [password-******] // This is just an example.
```

## Install

`npm install` in the project root will install dependencies in both `client` and `server`. 

Some basic Git commands are:

```
git clone [YOUR_REPOSITORY_URL]
cd project
npm install
```

## ENV

Create `.env` file for both client and server. See examples:

## Start development

```
npm run dev
```

## Languages & tools

-   [Node](https://nodejs.org/en/)

-   [Express](https://expressjs.com/)

-   [Mongoose](https://mongoosejs.com/)

-   [React](https://reactjs.org/)

-   [Webpack](https://webpack.js.org/)

### Code Formatter

-   Add a `.vscode` directory
-   Create a file `settings.json` inside `.vscode`
-   Install Prettier - Code formatter in VSCode
-   Add the following snippet:

```json

    {
      "editor.formatOnSave": true,
      "prettier.singleQuote": true,
      "prettier.arrowParens": "avoid",
      "prettier.jsxSingleQuote": true,
      "prettier.trailingComma": "none",
      "javascript.preferences.quoteStyle": "single",
    }

```

## About the Maintainer

This project is actively maintained by Priyal Shah.

**Priyal Shah**
*   **Title:** Software Developer
*   **Email:** priyalshah04845@gmail.com

With years of professional experience, Priyal brings expertise in data analysis and development, including skills in SQL, Python (Pandas, NumPy), R, and DAX.
