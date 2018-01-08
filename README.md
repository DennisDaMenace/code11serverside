
# code11serverside
Code 11 server side functionality


# Project Name

**Author**: Dennis - Aaron - Ayanle
**Version**: 1.0.0 Set up server side scaffold using basic client server side js.

1.5.0 Added data.json file for book library data, added 404.html file not found to Public facing folders

## Overview
We are attempting to implement a basic full stack application for a book list which will render books from a PostgreSQL database. Our company is building two sides of the full stack (client/server side)to store books lists in a database. A user will be able to  make a request to the server for retrieval of all books, which will then be rendered as a list in the browser (from client side).

## Getting Started - Server Side
1. Set up the server side scaffold - by using basic client side  package.json and all necessary dependencies
2. Adding postgres functionality to bring in all book data, as well being able to manipulate the data coming from the database being created on the client side being added. Used 
3. using Heroku as client to post results

## Architecture
We had to ensure we added the following dependencies to our server.js:
 "body-parser": "^1.18.2",
    "express": "^4.16.2",
    "dotenv": "^4.0.0",
    "pg": "^6.4.2"
Added 404.html file

## Change Log
01-07-2018 1:17 pm Ayanle - refactored server side app
01-07-2018 3:40 pm Ayanle - Code 11 service side functionality

/* get all books */ GET: https://server-lab10-codefellows.herokuapp.com/api/v1/books

/* add a new book */ POST: https://server-lab10-codefellows.herokuapp.com/api/v1/books/addNewBook

/* get a single book */ GET; GET: https://server-lab10-codefellows.herokuapp.com/api/v1/books/:id

/* update a specific book */ PUT: GET: https://server-lab10-codefellows.herokuapp.com/api/v1/books/updateBook/:id

/* delete a specific book */ DELETE: https://server-lab10-codefellows.herokuapp.com/api/v1/books/deleteBook/:id

/* delete ALL books */ DELETE:  https://server-lab10-codefellows.herokuapp.com/api/v1/books/deleteAllBooks

