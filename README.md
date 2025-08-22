# Inventory Management System

A comprehensive React-based inventory management system designed for TechSL to manage their inventory efficiently. The application provides role-based access control with separate interfaces for managers and employees.

## Project Background

This project was created as the frontend component of a MERN stack web application for the Rapid Application Development group assignment. The system was developed demonstrating modern React development practices.

**Project Details:**
- **Client:** techSL
- **Purpose:** Group assignment for Rapid Application Development course
- **Architecture:** React frontend with Material-UI components
- **Focus:** Inventory management system frontend with role-based user interfaces

## Features

🔐 **User Authentication & Authorization**
- Separate registration and login for Managers and Employees
- JWT token-based authentication
- Role-based access control with different permissions

📦 **Inventory Management**
- Managers: Full inventory oversight, product categories, and product management
- Employees: Add and update inventory items with selling prices and quantities
- Real-time inventory tracking with dates and pricing information

🛍️ **Product & Category Management**
- Create and manage product categories
- Add new products with category assignments
- Update existing product information
- Product ID and name management

👥 **Customer Management**
- Add new customers to the system
- Update existing customer information
- Customer database for order processing

📋 **Order Management**
- Create new orders for customers
- View comprehensive order history
- Detailed order information and tracking
- Order updates and modifications

🎯 **Role-Based Features**

**Manager Dashboard**
- Complete inventory overview
- Product category management
- Customer management
- Order history and tracking

**Employee Dashboard**
- Inventory viewing and updates
- Customer management
- Order creation and management
- Inventory additions with pricing

## Technology Stack

**Frontend:**
- React 18+ with Create React App
- UI Framework: Material-UI (MUI) v5
- Routing: React Router v6
- HTTP Client: Axios
- State Management: React Context API
- Authentication: JWT tokens
- Styling: CSS with Material-UI components


## Getting Started

This project was bootstrapped with Create React App.

### Available Scripts

In the project directory, you can run:

#### `npm start`
Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

#### `npm test`
Launches the test runner in the interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`
Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`
**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting
This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size
This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App
This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration
This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment
This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify
This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
