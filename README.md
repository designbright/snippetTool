#snippetTool

Using Passport, Node, Express, and MongoDB and Mongoose, create an application that organizes code snippets that you save for later use.

Using Express, Mustache, and express-session, create an app with a login page. When a user goes to /, and they are not logged in, redirect them to /login/. Upon entering a valid username and password, they should be authenticated and sent back to /. The root page should show that they are logged in and what username they are logged in as.

The valid usernames and passwords should be kept as a data structure in your application.
Add a logout link or button to the root page that logs the user out.
Add a signup page, linked to from the login page, that allows users to create a new account.

##Getting Started

In Terminal, cd to project
Find which file is your main app.js file  
Type
  node <nameoffile>.js
  node index.js


In browser, type localhost:3000 and your app should run

Login Screen
  Username: pongjones
  Password: pbj

###View Mongo Databases and Collections
  In terminal, cd to project folder
  type mongo
  type show dbs
  type use <nameofcollection> codeSnippetDB
  type show collections
  type db.nameofcollection.find()

  To exit MongoDB, type control + c
