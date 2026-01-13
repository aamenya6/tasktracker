# TaskTracker MERN Application

## 📌 Project Overview

TaskTracker is a simple MERN (MongoDB, Express, React, Node.js) application that allows users to:

- Add tasks
- View tasks
- Mark tasks as completed
- Delete tasks

The application demonstrates:

- A RESTful API built with Node.js and Express
- A React frontend built and served as static files
- MongoDB Atlas as the cloud database
- Deployment to Microsoft Azure App Service

This project was created as part of a cloud deployment practical assignment.

## 🧱 Technologies Used

- **Frontend:** React (Vite)
- **Backend:** Node.js, Express
- **Database:** MongoDB Atlas
- **ODM:** Mongoose (latest version)
- **Hosting:** Microsoft Azure App Service

## 📁 Project Structure

backend/
├── public/ # React production build
├── models/
│ └── Task.js
├── routes/
│ └── taskRoutes.js
├── server.js
├── package.json
└── .env (local only, not committed)

## Install dependencies

npm install

## Create a .env file in the backend folder

MONGO_URI=your_mongodb_atlas_connection_string
PORT=5000

## Run the server

npm run dev

## Deployment on Microsoft Azure

Steps Summary:
 - Create an Azure App Service (Web App)
 - Choose Node.js runtime
 - Set environment variables in Azure:
   - MONGO_URI
   - PORT
 - Enable Local Git deployment
 - Push the backend folder to Azure
 - Azure automatically builds and deploys the app

## Author

Name: Abel Nyarunda
Project: Cloud Deployment Practical – MERN Stack on Azure

## License

Copyright <2026> <ABEL NYARUNDA>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.