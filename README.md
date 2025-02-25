# Chatty: Real-Time Chat Application

This is a real-time chat application built using the MERN stack. The frontend is developed with ReactJS, Tailwind CSS, and DaisyUI, while the backend is built with Node.js, Express.js, MongoDB, and Socket.io. Zustand is used for state management on the frontend.

## Table of Contents

- [Introduction](#introduction)
- [File Structure](#file%structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

Welcome to the Real-Time Chat Application! This platform is designed to facilitate real-time communication between users. Users can sign up, log in, chat with others, check active statuses, and personalize their profiles and settings.

## File Structure
```
./
├── frontend/
├── backend/
├── package.json 
└── README.md              # Project documentation
```
### Frontend
```
frontend/
├── public/                # Static files (images, fonts, etc.)
│   └── ...
├── src/                   # Application source code
│   ├── components/        # Reusable UI components
│   │    ├──skeletons      #reusable skeletons
│   ├── assets/            # Container components (stateful)
│   │   └── ...
│   ├── pages/             # React.js page components
│   │   └── ...
│   ├── constants/         # maintaing theme for UI  
│   │   └── ... 
│   ├── lib/               # Utility libraries and helper functions
│   │   └── ...
│   ├── store/             # State mangament using Zustend 
│   │   └── ...
│   ├── App.jsx            
│   │   └── ...
│   ├── main.jsx           
│   │   
│   ├── index.css             
│      
│     
│              
│  
├── .env                   # Environment variables
├── .eslintrc.js           # ESLint configuration
├── Index.html             # main file
├── vite.config.js         # React.js configuration
├── package.json           # Project dependencies and scripts
├── tsconfig.json          # TypeScript configuration
└── README.md              # Project documentation
```
### Backend:
```
backend/
├── src/                   # Backend source code
│   ├── controllers/       # API event controllers
│   │   └── ...     
│   ├── lib/               # Utility libraries and helper functions
│   │   └── ...
│   ├── middleware/        # Middleware for auth and socket.io
│   │   └── ...
│   ├── models/            # Database models
│   │   └── ... 
│   ├── routes/            #API route definitions
│   │   └── ...
│   ├── index.js           # server file
│      
│   
├── .env                   # Environment variables
├── package.json           # Project dependencies and scripts
└── package-lock.json


```
## Features

- **Real-time Chat:** Chat with anyone who has signed up and logged in.
- **Active Status:** Check if a user is currently active.
- **Profile Page:** Change your profile picture and view your details.
- **Settings Page:** Change the theme according to your preference, and it will reflect across the entire web page.
- **Authentication:** 
  - Sign up and log in to use the chat features.
  - Only logged-in users can chat.
  - Users cannot chat when logged out.

## Installation

To get started with Algo Arena, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Nishantdas77/Chat-App.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd Chat-App
    ```

3. **Backend Setup**:
    - Navigate to the server directory:
      ```bash
      cd backend
      ```
    - Create a `.env` file in the server directory with the following variables:
      ```env
      PORT=my_port
      MONGODB_URI=mongodb_uri
      JWT_SECRET=jwt_secret
      NODE_ENV=node_env
      CLOUDINARY_CLOUD_NAME=cloudinary_cloud_name
      CLOUDINARY_API_KEY=cloudinary_api_key
      CLOUDINARY_API_SECRET=cloudinary_api_secret
      ```
    - Install dependencies and run the backend server:
      ```bash
      npm install
      npm run dev
      ```

4. **Frontend Setup**:
    - Navigate to the frontend directory:
      ```bash
      cd frontend
      
    - Install dependencies and run the frontend server:
      ```bash
      npm install
      npm run dev
      
## Usage

Follow these steps to use the Real-Time Chat Application:

1. **Sign Up:**
   - Navigate to the Sign-Up page.
   - Fill in the required details (username, email, password, etc.).
   - Click on the "Sign Up" button to create your account.

2. **Log In:**
   - Navigate to the Log-In page.
   - Enter your registered email and password.
   - Click on the "Log In" button to access your account.

3. **Chat with Users:**
   - Once logged in, you can start chatting with other users who are also logged in.
   - Use the chat interface to send and receive messages in real-time.

4. **Profile Page:**
   - Navigate to your Profile page.
   - Update your profile picture and view your account details.
   - Save changes to update your profile.

5. **Settings Page:**
   - Navigate to the Settings page.
   - Change the theme according to your preference.
   - The selected theme will be applied to the entire web page.

6. **Log Out:**
   - To log out, click on the "Log Out" button.
   - Once logged out, you will not be able to chat until you log in again.

## Contributing

Contributions are welcome and greatly appreciated! To contribute to this project, please follow these steps:

1. **Fork the Repository:**
   - Click the "Fork" button at the top right corner of this repository to create a copy of the repository under your own GitHub account.

2. **Clone the Repository:**
   - Clone the forked repository to your local machine using the following command:
     ```bash
     git clone https://github.com/your-username/your-forked-repository.git
     ```

3. **Create a New Branch:**
   - Create a new branch for your feature or bug fix:
     ```bash
     git checkout -b feature-or-bugfix-description
     ```

4. **Make Changes:**
   - Make your changes to the codebase.
   - Ensure that your code follows the project's coding style and guidelines.

5. **Commit Changes:**
   - Commit your changes with a descriptive commit message:
     ```bash
     git commit -m "Description of the changes made"
     ```

6. **Push Changes:**
   - Push your changes to the new branch on your forked repository:
     ```bash
     git push origin feature-or-bugfix-description
     ```

7. **Create a Pull Request:**
   - Navigate to the original repository and click on the "New Pull Request" button.
   - Select your branch from the forked repository and submit your pull request for review.

8. **Review Process:**
   - Your pull request will be reviewed by the maintainers.
   - You may be asked to make additional changes or provide clarification.

9. **Merge:**
   - Once your pull request is approved, it will be merged into the main branch.

Thank you for contributing to this project! Your efforts help make this project better for everyone.

## Contact

If you have any questions, feedback, or inquiries, feel free to reach out:

- **Name:** [Nishant Kumar Das]
- **Email:** [dasnishant7777@gmail.com]
- **GitHub:** [https://github.com/Nishantdas77](https://github.com/Nishantdas77)

We appreciate your interest in our project and look forward to hearing from you!


  


