# myFlix React App

## Objective
Using React, build the client-side for an app called myFlix based on its existing server-side code (REST API and database). API can be found here [myFlix-API](https://github.com/JarJarDinks/myFlix-API)

## Deployment
[Site Link](https://themovieflicks.netlify.app/)

## App Images
This is the Login Page: ![login](https://github.com/JarJarDinks/myFlix-client/assets/104926747/160388e9-66db-43aa-9370-5dbc5dc3a2ee)

This is the Home Page: ![mainpage](https://github.com/JarJarDinks/myFlix-client/assets/104926747/384b5ba0-f01e-4a4a-900a-3a443c0980d6)

This is the Movie Page: ![movievview](https://github.com/JarJarDinks/myFlix-client/assets/104926747/7237d0a6-d00b-4dc0-9837-7f285b3a27eb)

This is the Profile Page: ![profileveiw](https://github.com/JarJarDinks/myFlix-client/assets/104926747/153434b4-cbff-4c9c-9ce7-94e05faa2d10)

## Technologies Used
- React
- MongoDB
- Express
- Node.js
- ES2015+
- Bootstrap
- Parcel
- React Redux

## What I learned
- Building the client-side of a web application using React
- Understanding full-stack JavaScript development using the MERN stack
- Implementing state routing and sharing URLs in a single-page application
- Creating a responsive and polished user interface
- Using Bootstrap for styling and responsiveness
- Managing application state with React Redux

## Features
### Essential Views & Features:
1. Main view:
   - Returns ALL movies to the user (each movie item with an image, title, and description)
   - Filtering the list of movies with a "search" feature
   - Ability to select a movie for more details
   - Ability to log out
   - Ability to navigate to the Profile view

2. Single Movie view:
   - Returns data (description, genre, director, image) about a single movie to the user
   - Allows users to add a movie to their list of favorites
   - Display a list of related or similar movies

3. Login view:
   - Allows users to log in with a username and password

4. Signup view:
   - Allows new users to register (username, password, email, date of birth)

5. Profile view:
   - Displays user registration details
   - Allows users to update their info (username, password, email, date of birth)
   - Displays favorite movies
   - Allows users to remove a movie from their list of favorites
   - Allows existing users to deregister
