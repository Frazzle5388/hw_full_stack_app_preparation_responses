# hw_full_stack_app_preparation_responses

What is responsible for defining the routes of the games resource? A: Express server
What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for? A: The client is responsible for making GET requests to the server and the server is responsible for responding to said requests, the server should keep running, waiting for clients to make requests to it so that it can respond appropriately(Nodemon)
What are the the responsibilities of server.js? A: Listen to requests from the fron end and send to and receive requests from the Mongodb
What are the responsibilities of the gamesRouter? A:To enable GET, POST, PUT and DELETE requests
What process does the the client (front-end) use to communicate with the server? Sends a GET request
What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs A: we can chain another .then on to it and continue to work with the response till we have what we want.
Which of the games API routes does the front-end application consume (i.e. make requests to)?
What are we using the MongoDB Driver for? A: The driver features an asynchronous API that you can use to access method return values through Promises or specify callbacks to access them when communicating with MongoDB.
