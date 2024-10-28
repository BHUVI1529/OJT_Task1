# Role-Based Authentication Module - Frontend

## Description
This frontend project is built using React to provide a user interface for the Role-Based Authentication (RBAC) system.
It enables users to register, log in, and access different dashboards based on their roles (Admin, User).

## Features
- User login and registration forms.
- Axios for API requests to the backend.
- Conditional rendering of components based on user roles.
- Admin Dashboard with additional controls.
- User Dashboard with standard features.
- Proper error handling for restricted access.

## Installation

### Prerequisites
- Node.js (v14 or later)
- npm (Node Package Manager)
-  npm install is the command to install all the packages

### Steps to Set Up
1. **Create a new React application** (if not already created):

- npx create-react-app rbac-frontend
- cd rbac-frontend
   
3. Clone the repository:

- git clone https://github.com/your-username/OJT_Task1.git
- cd OJT_Task1
- git checkout frontend
   
4. Install Axios for API requests:
- npm install axios

# Usage:
To start the React application:
- npm start
- Access the application at http://localhost:3000.
- Login: Users can log in using their credentials.
- Register: New users can create an account.

# Environment Variables:
- Update the API base URL in your Axios configuration file to point to your backend server.
- For example, in src/authService.js, set:
  const API_URL = "http://localhost:8080/auth/";

# Deployment:
- install the gh-pages package
-  The package allows us to publish build files into a gh-pages
-  npm install gh-pages --save-dev
-  configure the package.json file so that we can point our GitHub repository to the location where our React app will be deployed.
-  add predeploy and deploy scripts to the package.json file.
-  "predeploy" : "npm run build",
- "deploy" : "gh-pages -d build",
- git add .
- git commit -m "setup gh-pages"
- git push
- npm run deploy

# Contributions:
-Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes and push to your branch.
- Create a pull request.

# License:
- This project is licensed under the MIT License
