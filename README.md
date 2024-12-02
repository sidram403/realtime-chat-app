# Real Time Chat App

# Project Setup Guide

This guide will walk you through setting up the project locally, including the frontend and backend.

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js (Recommended version: 14.x or above)
- MongoDB instance running (Local or Cloud)
- Cloudinary account for media uploads

## 1. Clone the Repository

Clone the GitHub repository to your local machine:

```bash
git clone https://github.com/sidram403/realtime-chat-app.git
```

## 2. Add Environment Variables
In the backend folder of the project, create a .env file and add the following content:

```
MONGODB_URL=<your-mongodb-url>
PORT=<your-port>
JWT_SECRET=<your-jwt-secret>
CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
CLOUDINARY_API_KEY=<your-cloudinary-api-key>
CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>

NODE_ENV=development
```
Make sure to replace the placeholder values with the actual credentials:

- your-mongodb-url: URL to your MongoDB instance.
- your-port: The port your backend will run on (default is 5000).
- your-jwt-secret: A secret key for generating JWT tokens.
- `your-cloudinary-cloud-name`, `your-cloudinary-api-key`, `your-cloudinary-api-secret`: Your Cloudinary credentials for media uploads.

## 3. Set Up the Frontend
Navigate to the frontend directory inside your project:
```bash
cd frontend
```
Run the following commands to install the dependencies and start the frontend server:
```bash
npm install
npm run dev
```
After the installation, the frontend will be available at http://localhost:5173.

## 4. Set Up the Backend
Now, go to the backend directory:
```bash
cd backend
```

Run the following commands to install the dependencies and start the backend server:
```bash
npm install
npm run dev
```

The backend will be running on the port specified in your .env file (default is 5001).

## 5. Access the Application
Once both the frontend and backend are running, you can access the application in your browser:

```arduino
http://localhost:5173
```
The frontend will communicate with the backend to fetch and send data.



