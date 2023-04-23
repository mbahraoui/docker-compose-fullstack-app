docker-compose-fullstack-app
This repository contains a Docker multicontainer application using Docker Compose. The app consists of a ReactJS frontend, a NodeJS backend, and a MongoDB database. Use this repository to easily set up and deploy the full stack application in a containerized environment.

Prerequisites
Before you can run this application, you need to have the following installed on your machine:

Docker
Docker Compose
Running the Application
To run the application, simply clone this repository to your machine and run the following command in the root directory:

Copy code
docker-compose up
This will build and start the application in a containerized environment. You can then access the frontend by navigating to http://localhost:3000 in your web browser.

Customizing the Application
If you want to customize the application, you can modify the source code in the frontend and backend directories. Once you have made your changes, simply run the docker-compose up command again to rebuild and restart the application.
