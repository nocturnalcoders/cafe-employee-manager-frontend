Café Employee Manager Frontend

Apology and Update

Dear Users,

I want to apologize for not implementing TanStack Query and TanStack Router as initially planned. Due to time constraints and research requirements, I have used axios for data fetching and react-router-dom for routing, as these are the tools I am more familiar with. Implementing TanStack Query and TanStack Router would have required additional time for research and integration.

Thank you for your understanding, and I appreciate your patience.

Overview

The Café Employee Manager Frontend is a React application designed to interact with the Café Employee Manager Backend. It provides a user-friendly interface for managing cafés and employees, including functionalities for creating, updating, and deleting records.

Features

Café Management: Interface for managing café records.
Employee Management: Manage employee records and their association with cafés.
User Interface: Responsive and styled with Material-UI or Ant Design.
Data Fetching and Routing: Utilizes React Router for navigation.
Requirements

Node.js: Ensure that Node.js (version 18 or higher) is installed on your system.
npm: npm is used to manage dependencies.
Getting Started

Prerequisites
Node.js: Install Node.js from nodejs.org.
npm: Included with Node.js.

Configuration
Install Dependencies: Navigate to the project directory and install the required npm packages:

[npm install]

[npm start]

[npm run build]

[docker build -t cafe-employee-manager-frontend .]

Run the Docker Container
[docker run -p 5000:80 --name cafe-employee-manager-frontend cafe-employee-manager-frontend]

Stopping and Removing the Docker Container
[docker stop cafe-employee-manager-frontend]

To remove the stopped container, use:
[docker rm cafe-employee-manager-frontend]


