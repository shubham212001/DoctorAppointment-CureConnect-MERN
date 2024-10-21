# DoctorAppointment-CureConnect-MERN

## Overview

DoctorAppointment-CureConnect-MERN is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to book appointments with doctors, view doctor profiles, and manage their appointments. It also includes an admin panel for managing doctors and appointments.

## Features

- User authentication and authorization
- Browse and search for doctors by specialty
- Book and manage appointments
- Admin panel for managing doctors and appointments
- Responsive design

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- Tailwind CSS
- Axios
- React Router
- React Toastify

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/DoctorAppointment-CureConnect-MERN.git
    cd DoctorAppointment-CureConnect-MERN
    ```

2. Install dependencies for the backend:

    ```bash
    cd backend
    npm install
    ```

3. Install dependencies for the frontend:

    ```bash
    cd ../frontend
    npm install
    ```

4. Install dependencies for the admin panel:

    ```bash
    cd ../admin
    npm install
    ```

## Environment Variables

Create a `.env` file in the `backend` directory and add the following environment variables:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=admin_email
ADMIN_PASSWORD=admin_password
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

Create a `.env` file in the `frontend` directory and add the following environment variables:

```
VITE_BACKEND_URL=your_backend_url
```

## Running the Application

1. Start the backend server:

    ```bash
    cd backend
    npm start
    ```

2. Start the frontend development server:

    ```bash
    cd ../frontend
    npm run dev
    ```

3. Start the admin panel development server:

    ```bash
    cd ../admin
    npm run dev
    ```

## Usage

- Open your browser and navigate to the frontend URL (usually `http://localhost:3000`) to access the user interface.
- Navigate to the admin panel URL (usually `http://localhost:3001`) to access the admin interface.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Contact

Created by Shubham Sharma. You can reach me at shubham.sharma200121@gmail.com.

