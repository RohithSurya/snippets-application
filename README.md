# Snippets Application

This is a full stack web application I worked during Fall'23 semester as part of Advanced Web Programming course at CalState LA.

- The app allows users to write code snippets that can be viewed and bookmarked by other users.
- Login/Register functionality is implemented for users to access personalized dashboard and feed.
- Users can select their topics (programming languages) for the personalized feed.
- Based on the user roles, users can/cannot perform some actions.

# Technologies & Frameworks Used

**Backend**: [Node.js](https://nodejs.org/en), [Express.js](https://expressjs.com/), [Mongoose](https://mongoosejs.com/), [bcrypt](https://www.npmjs.com/package/bcrypt)

**Frontend**: [Vue.js](https://vuejs.org/), [axios](https://axios-http.com/), [tailwindcss](https://tailwindcss.com/)

**Database**: [Mongo DB](https://www.mongodb.com/)

# Features

**Building a Node.js RESTful Server Application**

- Implements a Express.js s
- Building a Node.js Server Application.
- Implement RESTful routes to manage resources.
- Development of the backend logic for handling HTTP requests and responses.

**Adding JWT to the Node.js Server Application and Connecting to MongoDB**

- Incorporate the MVC design pattern
- Implement schemas and data models
- Connect to MongoDB to store application data

**Creating a Vue.js Frontend for the Node.js Server Application**

- Enhance Snippet Application by using JWTs for user management
- Develop a dynamic and interactive user interface using Vue.js.
- Establish communication between the Vue.js frontend and the Node.js backend

# Installation

Clone the repository

## Backend

### Install the dependencies

```bash
cd snippet-server
npm install # Installs the backend dependencies
```

### Running the application

**To run the application mongo atlas account is required**

Go to `config.json` in `snippet-server` to replace the values of `username` and `password` with your mongo atlas credentials.

```bash
npm run start # Nodemon Automatically restarts based on file changes
```

The application is served at http://localhost:8080

## Frontend

### Install the dependencies

```bash
cd snippet-client
npm install # Installs the frontend dependencies
```

### Running the application

```bash
npm run dev
```

The frontend is served at http://localhost:5173

## Improvements

- UI is pretty basic at best and needs to be revamped.
- An ML model/suggestion algorithm can be used to give more personalized feed.
- The feed doesn't show the bookmarks of the current snippet.

---

Shout out to [Cydney Auman](https://www.linkedin.com/in/cydneyauman/) for teaching this class.
