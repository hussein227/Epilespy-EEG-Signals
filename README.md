# Epilespy-EEG-Signals
Classify People as Epilespy and Normal people we cleaning DatasSet Then we Do Feature Extraction Then Modeling 
### how to run the project
```python
   Google Colab
```
## Table of Contents
- [Project Description](#project-description)
- [Motivation](#motivation)
- [Code Styles](#code-styles)
- [Tools and Frameworks](#tools-and-frameworks)
- [Build Status](#build-status)
- [Code Examples](#code-examples)
- [Features](#features)
  * [Admin Functionalities](#administrator)
  * [Instructor Functinalities](#instructor)
  * [Individual Trainee Functinalities](#individual-trainee)
  * [Corporate Trainee Functinalities](#corporate-trainee)
  * [guest Functionalities](#guest)
- [API References](#api-references)
  * [Guest (Course) router](#guest-router)
  * [Instructor router](#instructor-router)
  * [Trainee router](#trainee-router)
  * [Admin router](#admin-router)
  * [Authentication router](#authentication-router)
- [Testing](#testing)
- [Contributing](#contributing)
- [Credits](#credits)
- [Installation](#installation)
- [How to use](#How-to-use)
- [Licence](#Licence)

## Project Description
### Title 
Canadian Chamber Of Commerce
### Course 
Advanced Computer Lab (CSEN 704), Winter 2022

### Theme
The theme of the project, is to create a complete Online Learning System. An Online
Learning System is a web application through which individuals can attend pre-recorded
courses online. Existing web applications include but are not limited to Coursera, Udemy,
LinkedIn Learning, Great Learning and Udacity.


### Overview 
This project followed the Agile Methodology; meaning it was splited into Sprints, with
each Sprint lasting a set amount of time and a fully functioning version of the project
with the specified System Requirements should be submitted and evaluated.

### Objectives
- Learn how to properly use the Agile Methodology to plan out a project and develop
the software.
- Learn the process of following a given set of System Requirements to develop a
software.
- Learn to research and master the use of the MERN Stack.
- Learn how to work together as a team on GitHub.

## Motivation
The project is done as a group for a german university course (Advanced Computer lab) and This project is done as a simulation to real company working flow where all team members contribuite together for a final project. which motivated us to put our efforts on a project where we can learn new technologies along side with implementing them on a real application .We make an online courses website to encourage people
to develop their skills and make this process easy by learning from home. 
## Code Styles
The project is formatted using `prettier` also The project follows the  [ MVC ](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)design pattern ,MVC is a software architectural pattern commonly used for developing user interfaces that divide the related program logic into three interconnected elements. This is done to separate internal representations of information from the ways information is presented to and accepted from the user , So the Files in the backend was divided into the M (models) where the schema of the models exist which represent the core of the database , the C (controller) where the functions needed for the routes exists and the V (views) the view in MERN stack is represented by the react frontend server. Also the routes in our project was abstracted from the controller function as shown in [ API References](#api-references)

## Tools and Frameworks
![MERN_STACK](https://miro.medium.com/max/1400/1*FVtCyRdJ6KOr4YswTtwMeA.jpeg)

### What is the MERN Stack?
MERN stands for MongoDB, Express, React, Node, after the four key technologies that make up the stack.

- MongoDB - document database
- Express(.js) - Node.js web framework
- React(.js) - a client-side JavaScript framework
- Node(.js) - the premier JavaScript web server

Express and Node make up the middle (application) tier. Express.js is a server-side web framework, and Node.js the popular and powerful JavaScript server platform. Regardless of which variant you choose, ME(RVA)N is the ideal approach to working with JavaScript and JSON, all the way through.

### How does the MERN stack work?
The MERN architecture allows you to easily construct a 3-tier architecture (frontend, backend, database) entirely using JavaScript and JSON.

![MERN_ARCH](https://webimages.mongodb.com/_com_assets/cms/mern-stack-b9q1kbudz0.png?auto=format%2Ccompress)

#### - React.js Front End
The top tier of the MERN stack is React.js, the declarative JavaScript framework for creating dynamic client-side applications in HTML. React lets you build up complex interfaces through simple Components, connect them to data on your backend server, and render them as HTML.

React’s strong suit is handling stateful, data-driven interfaces with minimal code and minimal pain, and it has all the bells and whistles you’d expect from a modern web framework: great support for forms, error handling, events, lists, and more.

#### - Express.js and Node.js Server Tier
The next level down is the Express.js server-side framework, running inside a Node.js server. Express.js bills itself as a “fast, unopinionated, minimalist web framework for Node.js,” and that is indeed exactly what it is. Express.js has powerful models for URL routing (matching an incoming URL with a server function), and handling HTTP requests and responses.

By making XML HTTP Requests (XHRs) or GETs or POSTs from your React.js front-end, you can connect to Express.js functions that power your application. Those functions in turn use MongoDB’s Node.js drivers, either via callbacks for using Promises, to access and update data in your MongoDB database.

#### - MongoDB Database Tier
If your application stores any data (user profiles, content, comments, uploads, events, etc.), then you’re going to want a database that’s just as easy to work with as React, Express, and Node.

That’s where MongoDB comes in: JSON documents created in your React.js front end can be sent to the Express.js server, where they can be processed and (assuming they’re valid) stored directly in MongoDB for later retrieval. Again, if you’re building in the cloud, you’ll want to look at Atlas. If you’re looking to set up your own MERN stack, read on!

## Build Status 
 - The project currently under development and there are some styling problems to be fixed 
- jest tests to be added

