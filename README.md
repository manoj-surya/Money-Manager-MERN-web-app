# Money-Manager-MERN-web-app
Description :
=>Money Manager is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides a convenient way to track your income and expenses, allowing you to effectively manage your budget.

# Technology Used
MongoDB: A NoSQL database used to store user information and transaction data.
React.js: A JavaScript library used for building the user interface and managing the frontend components.
Express.js: A web application framework used to build the backend server and handle API requests.
Node.js: A JavaScript runtime environment used to execute JavaScript code on the server side.

# Features
Register and Login Page
The application provides a user registration and login functionality. Users can create an account by providing their email address and password. They can then use their credentials to log in to the application.

# Home Page
Once logged in, users are directed to the home page where they can add their income and expenses. They can specify the type of transaction, amount, and category. The application stores the transactions in the database, allowing users to keep track of their financial activities.

# Chart Page
The chart page displays a visual representation of the user's budget. It presents the income and expense data in a graphical format, making it easier for users to analyze and understand their financial situation.

# Project Structure
=>Backend
  *Models: The usermodel and transaction models are created using MongoDB. They define the structure and schema for storing user information and transaction data.
Controllers: The userController.js and transactionCtrl.js files contain the logic for managing user registration, login, logout, and transaction operations (income/expense).
  *Server.js: This file imports all the necessary backend services and defines routes for handling API requests. It also implements Cross-Origin Resource Sharing (CORS) to allow global usage of the API. The server.js file is used to start the backend server.
Frontend

# Client: 
  The src folder contains the main frontend files.
  =>app.js and index.js: These files are responsible for rendering the React components and managing the frontend logic.
  =>style: This folder contains the CSS styles for the frontend files.
  =>pages: This folder contains the homepage, login, and register pages.
  =>components: This folder contains the layout and analytics components used in the application.

  
# Public
  index.html: This HTML file serves as the entry point for the application and is responsible for rendering the React components.
=>Build
The build folder contains the compiled and optimized version of the application. It is created when the application is built for production using tools like Webpack or Create React App.

# Conclusion
The Money Manager MERN web app provides a user-friendly way to track income and expenses, helping users effectively manage their budget. With its intuitive interface and visual representation of financial data, it simplifies the process of staying on top of personal finances.

Feel free to explore the project and try it out yourself!


