# 🌐 Cloud-Based Task Manager (MERN)

[![MERN Stack](https://img.shields.io/badge/MERN-Stack-green.svg)](https://mern.io/)


## 📋 Overview
The **Cloud-Based Task Manager** is a web application designed to streamline team task management. Built using the MERN stack (MongoDB, Express.js, React, and Node.js), this platform offers a user-friendly interface for efficient task assignment, tracking, and collaboration. It serves both administrators and regular users, enhancing productivity and organization.

## 💡 Problem Statement
In dynamic work environments, effective task management is essential for team success. Traditional methods, such as spreadsheets or manual tracking, can be cumbersome and error-prone. This application addresses these challenges by providing a centralized, cloud-based solution for seamless collaboration and improved workflow efficiency.

## 🔍 Features

### 👩‍💼 Admin Features
- **User Management:** 
  - Create and manage admin accounts.
  - Add and manage team members.
- **Task Assignment:**
  - Assign tasks to individuals or teams.
  - Update task details and statuses.
- **Task Properties:**
  - Label tasks as To Do, In Progress, or Completed.
  - Set priority levels: High, Medium, Normal, Low.
  - Manage sub-tasks.
- **Asset Management:**
  - Upload and manage task-related assets (e.g., images).
- **User Account Control:**
  - Enable/disable user accounts.
  - Permanently delete or trash tasks.

### 🧑‍💻 User Features
- **Task Interaction:**
  - Change task status to In Progress or Completed.
  - View detailed task information.
- **Communication:**
  - Add comments or chat within task activities.

### 🛡️ General Features
- **Authentication & Authorization:**
  - Secure login with role-based access control.
- **Profile Management:**
  - Update user profiles and manage settings.
- **Password Management:**
  - Securely change passwords.
- **Dashboard:**
  - Overview of activities with task filtering options.

## 🚀 Technologies Used

### **Frontend**
- React (Vite)
- Redux Toolkit for State Management
- Headless UI
- Tailwind CSS

### **Backend**
- Node.js with Express.js

### **Database**
- MongoDB for efficient and scalable data storage.


The Cloud-Based Task Manager is an innovative solution that brings efficiency and organization to task management within teams. By harnessing the power of the MERN stack and modern frontend technologies, the platform provides a seamless experience for both administrators and users, fostering collaboration and productivity.

&nbsp;

## SETUP INSTRUCTIONS


## Server Setup

## Environment variables
First, create the environment variables file `.env` in the server folder. The `.env` file contains the following environment variables:

- MONGODB_URI = `your MongoDB URL`
- JWT_SECRET = `any secret key - must be secured`
- PORT = `8800` or any port number
- NODE_ENV = `development`


&nbsp;

## Set Up MongoDB:

1. Setting up MongoDB involves a few steps:
    - Visit MongoDB Atlas Website
        - Go to the MongoDB Atlas website: [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas).

    - Create an Account
    - Log in to your MongoDB Atlas account.
    - Create a New Cluster
    - Choose a Cloud Provider and Region
    - Configure Cluster Settings
    - Create Cluster
    - Wait for Cluster to Deploy
    - Create Database User
    - Set Up IP Whitelist
    - Connect to Cluster
    - Configure Your Application
    - Test the Connection

2. Create a new database and configure the `.env` file with the MongoDB connection URL. 

## Steps to run server

1. Open the project in any editor of choice.
2. Navigate into the server directory `cd server`.
3. Run `npm i` or `npm install` to install the packages.
4. Run `npm start` to start the server.

If configured correctly, you should see a message indicating that the server is running successfully and `Database Connected`.

&nbsp;

## Client Side Setup

## Environment variables
First, create the environment variables file `.env` in the client folder. The `.env` file contains the following environment variables:

- VITE_APP_BASE_URL = `http://localhost:8800` #Note: Change the port 8800 to your port number.
- VITE_APP_FIREBASE_API_KEY = `Firebase api key`

## Steps to run client

1. Navigate into the client directory `cd client`.
2. Run `npm i` or `npm install` to install the packages.
3. Run `npm start` to run the app on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.



&nbsp;

## For Support, Contact:

- Email: asi.f.khan@hotmail.com
