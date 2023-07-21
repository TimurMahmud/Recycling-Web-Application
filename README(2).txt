README

Description

This repository contains the code for a web application that promotes recycling through competition and socialness. 
The application consists of a server-side and a client-side component, both of which need to be installed and configured before use.

Folder Structure

The main code of recycling-client is in the src folder which contains:
	assets - contains assets for the web app
	components - contains code for the main app functionalities
	features - contains code on users and authentication
	hooks - contains code fo hooks and states for users
	PrivateRoute - contains private route code
	Screens - contains code on the dashboard pages
	The rest of the project follows basic react app format

The main code of recycling-server folder which contains:
	connection - contains code which connects to database
	controllers - contain code on controllers used
	middleware - contains code on image upload and verification
	models - contains code on object models
	router - contains code on routers 	
	uploads - contains files uploaded by users
	utils - contains code on authentication tokens
	.env - contains environmental variables
	server.js - contains code to start server
	
Installation

Use Windows preferebly as localhost:5000 gets used by airplay on Mac. If you are on Mac however turn it off on Apple menu > System Preferences >Sharing.

Make sure to be on npm version 9.2.0 for the barcode scanning to work. (All will be made evident in video submission)
To check what version you are on type 'npm -v' in terminal and press Enter.
If you do not have npm download and install nodejs for your respective device at https://nodejs.org/en/download.

To install and run the application, follow these steps:

1)    Download the project as a zipped folder onto your desktop.

2)    Unzip the folder to reveal a folder, recycling-web-app, which has two subfolders within it, recycling-server and recycling-client.

3)    Open a terminal and navigate to the recycling-server subfolder using the cd command:
      'cd /path/to/recycling-server'

4)    Install the server-side dependencies by running the command 'npm install'.

5)    Start the server-side application by running the command 'npm start'. Leave this terminal open and open a new terminal.

6)    In the new terminal, navigate to the recycling-client subfolder using the cd command:
      cd /path/to/recycling-client

7)    Install the client-side dependencies by running the command 'npm install'.

8)    Start the client-side application by running the command 'npm run start'. The application should open locally in your default browser. If not, type http://localhost:3000/ into the URL and press Enter.

Usage

To use the recycling web application, follow these steps:

    To log in to an admin account, use email: admin@trashtalk.com and password: 12345Aa!
    To log in to a normal user account, use email: user@trashtalk.com and password: 12345Aa! , or create a new account.

Again, I would like to stress if the barcode scanning (will show functionality in video submission) is not working please try use npm version 9.2.0. Other than that Happy testing ! :)

Credits

This project was developed by Timur Mahmud as part of a final year university project.
All images used are free from unsplash.com