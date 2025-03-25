# Intern day_16
## Backend server
### This server is used for maintaing the attendance of an person.
- It stores the data of his Name,Age,Id and the total no.of.days the office was operational and how many days he is present and how many days he is absent,If he took an leave it holds the reson for the leave on the particular date .
- After creating the local server i'm using an array to hold all the data of the user.
- I programmed the function to do all this operation inside it whenever it called stores that data and information of that function into an array.
- Here for now i have used two methods POST and GEt.
- POST is used to Store an value or resource in to the array or database if we connected one,In bruno API tester we call it by Running its localhost and using this method we stores value in the array.
-GEt method is used to give an request for an particular data from the server and it bring that request to an server and returns the response for the request we have given.
- Both methods are using separate route to complete their task and using the route only we can call then or assign them the task through the API.
## Postgres
 ###  I have  created an backend server using express.js framework and here I uses postgresql as an database to store the data have been generated in my server,This postgres database is an sql based database it is an object relational database management.
 - we need to connect this database with the server we have created by impoRts the package 'pg' from the client.
 -  In postgres we use two connection methods which are CLient and pool.
 - Pool connection is an regularly used connection for the server most of the large data work environments are defaultly uses this connection for their server.
 - Client connection is uses in the development server which is being creating an base server to work on the local environment.
 - In postgres we need to setup an environment to work with and connect we have to create an separate and new database to store our data and we have to give an username and password for that data base.
 - For the client connection servers  we have to create our own schemas.
 - For our server which maintains the register of the office which governs the employee info and their leave record we have to create an table in the particular database we assigned to the server and create an table to store the values which is generated from the server by the request and operation made from both the server and the client siude which was generated through the Bruno API.
 - Here we are creating the required coloumns for the table which uses to store the data of the server into the table's particular coloumn  through an query which is generated inside the POST Method which uses to store an data and GET method is uses to retrieve the data from the server inside that command the server retrive the data from the database and send its to the client as an response for the request he gave.

