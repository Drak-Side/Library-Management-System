Library Management System
This project is a comprehensive Library Management System built with React on the frontend and Node.js with Express and MongoDB on the backend. It features:

User Roles: Distinct functionalities for Admins and Guests. Admins can manage book records and view price histories using Highcharts, while Guests can borrow and return books.
Dynamic Data Handling: MongoDB for data storage and management, with Express handling API requests.
Responsive UI: Built with React and Material-UI for a seamless user experience.
Technologies Used
Frontend: React, Material-UI, Highcharts
Backend: Node.js, Express
Database: MongoDB
Key Features
Admin Dashboard for book management
Guest functionality for borrowing and returning books
Data visualization for book price history
Setup and Run Backend
Navigate to Backend Directory


cd backend
Install Dependencies


npm install
Install MongoDB

Download MongoDB from here or follow the installation guide here for your OS.
Configure Environment Variables

Rename the .env.sample file to .env and configure it with your MongoDB connection details.
Start the Server


npm start
