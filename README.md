# Vistar

A common platform for job seekers and job providers for the local community which will include jobs for people who earn on the basis of daily wage with features like a review system,job trends and location based service.


## Objective
Using Restful web services, React JS, NodeJS MySQL, Kafka, NoSQL database MongoDB to create a prototype of LinkedIn. Our application consists of two main type of users: Applicant and Recruiter.

After logging in, the user gets presented with a different view of the system depending on the role i.e. the user is Applicant or Recruiter. If the logged in user is an Applicant, they are shown user dashboard which has the analytics of all the user activity on our website. We’ve used Charts.js library to display the graphs of all user activity.

Applicant has various functionalities such as Search and Apply for a Job, Messaging, Networking with people i.e. ability to connect with other people (implemented using GraphDB) and view and edit profile. Recruiter has various functionalities such as Posting a Job, Messaging, Networking with people i.e. ability to connect with other people (implemented using GraphDB) and view and edit profile.


## Tech Stack


This project uses the following technologies:

* React and React Router for frontend
* Express and Node for the backend
* MongoDB for the database
* Redux for state management between React components


## How to start

We’ll be creating a minimal full-stack login/authorization app using the MERN stack (MongoDB for our database, Express and Node for our backend, and React for our frontend). We’ll also integrate Redux for state management for our React components.

Our app will allow users to: 

* Register
* Log in
* Access protected pages only accessible to logged in users
* Stay logged in when they close the app or refresh the page
* Log out


This should be a solid base to build off for a more functional full-stack MERN app.This should also enable you to more effectively build out full-stack apps using any backend / frontend.


In this part, we will: 

* Initialize our backend using npm and install necessary packages
* Set up a MongoDB database using mLab
* Set up a server with Node.js and Express
* Create a database schema to define a User for registration and login purposes
* Set up two API routes, register and login, using passport + jsonwebtokens for authentication and validator for input validation
* Test our API routes using Postman


We’ll build our backend from scratch without boilerplate code, which I feel is more ideal for first learning about MERN apps.


### Prerequisites

You should have at least a basic understanding of fundamental programming concepts and some experience with introductory HTML/CSS/Javascript. If you don’t have experience with Javascript but have worked in Python, Ruby or another similar server-side language, you should still be able to follow along.

This is a good introduction to building a full-stack app. You can (and should) read more about the technologies included in the stack before getting started (Mongo, Express, React, Node).


### Install

Lastly, make sure you have the following installed.

* Text Editor (Atom) (or VS code/Sublime Text)
* Latest version of Node.js (we’ll use npm, or “Node Package Manager”, to install dependencies—much like pip for Python or gems for Ruby)
* MongoDB (quick install: install Homebrew and run brew update && brew install mongodb)
* Postman (for API testing)
* Prettier (to seamlessly format our Javascript; in Atom, Packages → Prettier → Toggle Format on Save to automatically format on save)


