# REST API School Database 

## Details:

* Using Postman, users can interact with database by retrieving a list of courses, as well as adding, updating and deleting courses in the database.
* User is required to create an account and log-in to make changes to database.

## Technologies Used:

* MongoDB, Mongoose, JavaScript, Node.js, Express.js

## Getting Started

To get up and running with this project, run the following commands from the root of the folder that contains this README file.

First, install the project's dependencies using `npm`.

```
npm install

```

Second, ensure that you have MongoDB installed globally on your system.

* Open a `Command Prompt` (on Windows) or `Terminal` (on Mac OS X) instance and run the command `mongod` (or `sudo mongod`) to start the MongoDB daemon.
* If that command failed then you’ll need to install MongoDB.
* [How to Install MongoDB on Windows](http://treehouse.github.io/installation-guides/windows/mongo-windows.html)
* [How to Install MongoDB on a Mac](http://treehouse.github.io/installation-guides/mac/mongo-mac.html)

Third, seed your MongoDB database with data.

```
npm run seed
```

And lastly, start the application.

```
npm start
```

To test the Express server, browse to the URL [http://localhost:5000/](http://localhost:5000/).
