# Expense_Tracker-Mern
This code is belongs to BradTraversy.

A front-End react web application and a Back-End web application is implement to create this project with mongoDb atlas as a database.

#Dependencies used:
<ul>
<li>Express </li>
<li>Dotenv</li>
<li>Mongoose</li>
<li>Path</li>
<li>Morgan</li>
</ul>

Dotenv is used to have Sensitive information regarding web application. Like, Port number , database information , current stage of your project(development , production) , etc.

#Route-transactions:
Put your routes in a seprate folder. Specify the type of requests associated with the routes.

#Controller-transactions: 
Handle the request specify by the route and send a respose to the client.

#db.js:
connect your database to your backend application.

#Model-Transaction:
Create a model. Create a schema according to your application and connect to your controller-transactions file.

#Middleware:
create a body parser middleware to fetch data from the client.

#Globalstate:
This is a frontend application file which sends requests to backend application Using "Axios".This file contains hooks and contex api.

#Appderucer:
appReducer is a file which contains functions to add functionalities and manipulate data provided by Global state using hooks.

#Deploy:
deploy your project. It,s been deployed to heroku using git and npm build libraries.



