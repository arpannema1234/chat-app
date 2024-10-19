# Chatting App

Welcome to the Chatting App! This project is a simple, user-friendly chat application that allows users to register, log in, and communicate with each other in real-time. The app is built using modern web development technologies and provides a seamless chat experience.

# Login Page

![image](https://github.com/user-attachments/assets/804ef7a4-68cb-44cb-a6ee-52457b77116e)

# Password Page

![image](https://github.com/user-attachments/assets/0f54a983-e0dc-4a96-b1a4-832ff377a179)

# Chat Page

![image](https://github.com/user-attachments/assets/d1ed0971-af54-4b16-9e29-9792702ebe38)

# Chats

![image](https://github.com/user-attachments/assets/2944a7cb-08c6-4e8b-9d06-d6d7e5d7fa89)

# Search User

![image](https://github.com/user-attachments/assets/c5496a96-84f5-40df-bb2f-747c1d049be7)

# Profile Page

![image](https://github.com/user-attachments/assets/030c7d7d-01fa-442d-a922-351dde414a30)


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)

## Features

- **User Registration and Authentication**: Secure user registration and login functionality using JWT.
- **Profile Management**: Users can upload a profile picture and manage their profile.
- **Real-time Chat**: Real-time messaging between users.
- **Responsive Design**: Works on both desktop and mobile devices.
- **Image Upload**: Users can upload images as part of their profile.

## Technologies Used

- **Frontend**:
  - React.js
  - React Router
  - Tailwind CSS
  - React Hot Toast for notifications
- **Backend**:
  - Node.js
  - Express.js
  - JWT (JSON Web Tokens) for authentication
  - Cloudinary for image storage
- **Others**:
  - Axios for HTTP requests
  - FormData API for file uploads

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Node.js
- npm (Node Package Manager)
- Cloudinary account

### Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/yourusername/chatting-app.git
    cd chatting-app


    ```

2.  Installation:

    ```bash
    npm install

    ```

3.  Set up Frontend environment variables:
    Create a .env file in the root_directory/client and add the following variables:

        ```env
        REACT_APP_BACKEND_URL=<your-backend-url>
        CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
        CLOUDINARY_API_KEY=<your-cloudinary-api-key>
        CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>

4.  Set up Frontend environment variables:
    Create a .env file in the root_directory/server and add the following variables:
    ```env
    FRONTEND_URL = http://localhost:3000
    MONGODB_URI = your_mongo_url
    JWT_SECREAT_KEY = your_JWT_secret_key
    ```
5.  Run the app:

    ```bash
    npm start
    ```

The app will be availaible on "http://localhost:3000"
