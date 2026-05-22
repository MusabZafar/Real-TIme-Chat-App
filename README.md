# Real-TIme-Chat-App
The Chatter Backend project is a personal learning journey where I’ve built a scalable, production-grade full-stack chat application. The goal of this project is to help me gain hands-on experience with NestJS, GraphQL, MongoDB, and React while learning how to deploy a real-world application to AWS.

# Chatter Backend

This is a full-stack chat application project built using **NestJS** for the backend and **React** for the frontend. The application is designed to be scalable and production-grade, enabling real-time messaging between users.

## Features

- **Full-stack application** with NestJS backend and React frontend.
- **GraphQL API** for managing CRUD operations and messaging subscriptions.
- **WebSocket-based messaging** for real-time updates.
- **JWT authentication** for securing the application.
- **Material UI** for a responsive and modern frontend design.
- **Apollo Client** for state management and interacting with the GraphQL API.
- **MongoDB** as the database for storing data.
- **AWS Elastic Beanstalk & Amplify** deployment with CI/CD pipeline for continuous delivery.

## Tech Stack

- **Backend:** NestJS, GraphQL, MongoDB
- **Frontend:** React, Material UI, Apollo Client
- **Deployment:** AWS Elastic Beanstalk, AWS Amplify
- **CI/CD:** Continuous Delivery via AWS services

## Getting Started

### Prerequisites

- Node.js (>= 14.x)
- MongoDB (or a running MongoDB instance)
- AWS account for deployment

###Install dependencies:

npm install


Configure MongoDB settings in the .env file.

###Start the NestJS server:

npm run start


###In another terminal, start the React frontend:

cd frontend
npm install
npm start

###Deployment

The application can be deployed on AWS Elastic Beanstalk and AWS Amplify.

###Push the backend code to Elastic Beanstalk:

eb init
eb create
eb deploy


For frontend deployment with AWS Amplify, follow the official Amplify documentation for deploying React apps.
