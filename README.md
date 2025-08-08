# Memories - Social Media MERN App

![Memories](https://i.ibb.co/Z8Y0CJv/Screenshot-2020-10-30-at-11-10-04.png)


Memories is a full-stack social media application built with the MERN stack (MongoDB, Express.js, React, Node.js). It provides a platform for users to share their most memorable moments with a community of friends. Users can create, update, like, and delete their posts, creating a dynamic and interactive experience.

This project was built to demonstrate a comprehensive understanding of full-stack development, including user authentication, RESTful API design, and complex state management with Redux.

Live Demo & Screenshot
Live Demo: [YOUR_DEPLOYMENT_LINK_HERE]

##Features
Full CRUD Functionality: Users can Create, Read, Update, and Delete their own posts.

User Authentication: Secure user registration and login system using JSON Web Tokens (JWT) for protected routes and actions.

Post Interaction: Users can "like" posts from other users, with real-time updates to the like count.

Image Uploads: Functionality to upload images with posts, which are converted to Base64 format for storage.

State Management: Utilizes Redux for robust and predictable state management across the application, handling posts, authentication, and UI state.

Responsive Design: The user interface is fully responsive and built with Material-UI for a clean, modern look on all devices.

##Tech Stack
Frontend:

React

Redux

Material-UI

Axios

Backend:

Node.js

Express.js

Database:

MongoDB with Mongoose

##Setup and Installation
To get a local copy up and running, follow these simple steps.

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
Install server dependencies:


cd server
npm install
Install client dependencies:


cd ../client
npm install
Set up environment variables:

Create a .env file in the server directory.

Add your MongoDB connection string and a JWT secret:

CONNECTION_URL = 'your_mongodb_connection_string'
JWT_SECRET = 'your_jwt_secret'
Run the application:

From the root directory, run both the client and server concurrently:

npm start













