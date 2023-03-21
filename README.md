NodeBlog
=============

Blog Website

Description
-----------

This is a blog website built using Node.js and EJS. It allows users to create, read, update, and delete blog posts.

Prerequisites
-------------

Before you can run this application, you'll need to have the following software installed on your computer:

-   Node.js
-   npm
-   MongoDB Atlas account

Installation
------------

### Node.js

You can download and install Node.js from the [official website](https://nodejs.org/).

### npm

npm is included with Node.js, so once you have Node.js installed, you should have npm installed as well. You can check if npm is installed by running the following command in your terminal:

Copy code

`npm -v`

If you see a version number printed to the console, then npm is installed.

### MongoDB Atlas

This application uses MongoDB Atlas to store blog post data. You can create a free account at the [MongoDB website](https://www.mongodb.com/cloud/atlas).

Once you have an account, follow these steps:

1.  Create a new project and a new cluster.
2.  Create a new database and a new collection for your blog posts.

Configuration
-------------

Before you can run the application, you'll need to configure it with your MongoDB Atlas credentials.

1.  Create a new file named `.env` in the root directory of the project.
2.  Open the `.env` file in a text editor and add the following lines:

makefileCopy code

`MONGODB_URI=<your-mongodb-uri>`

1.  Replace `<your-mongodb-uri>` with your MongoDB Atlas connection string. You can find your connection string by following these steps:

    1.  Log in to your MongoDB Atlas account.
    2.  Navigate to the cluster that you created earlier.
    3.  Click the "Connect" button.
    4.  Select "Connect your application".
    5.  Select "Node.js" as the driver and "3.6 or later" as the version.
    6.  Copy the connection string that is displayed on the page.

    Your connection string should look something like this:

    Copy code

    `mongodb+srv://<username>:<password>@<cluster-name>.mongodb.net/<database-name>?retryWrites=true&w=majority `

2.  Save the `.env` file.

Running the Application
-----------------------

To run the application, follow these steps:

1.  Clone the repository to your local machine.

2.  Open a terminal window and navigate to the project directory.

3.  Run the following command to install the required dependencies:

    Copy code

    `npm install`

4.  Run the following command to start the application:

    sqlCopy code

    `npm start`

5.  Open your web browser and navigate to `http://localhost:4000` to view the application.

Built With
----------

-   Node.js
-   Express
-   EJS
-   MongoDB Atlas

Authors
-------

-   [Saruhan Sandokan Köle](https://github.com/SandokanSaruhan)

