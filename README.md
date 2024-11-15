# Car Management Application

A comprehensive full-stack application for managing car records, allowing users to perform CRUD operations, upload car images, and implement secure user authentication. Built with Node.js, Express, MongoDB, and deployed on a cloud platform.

## Features

- **CRUD Operations**: Create, read, update, and delete car records with ease.
- **Image Upload**: Supports multiple car image uploads with file size validation.
- **Authentication**: Secure user authentication for access control.
- **Search Functionality**: Find car records quickly using search filters.

## Technologies Used

- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **File Uploads**: Multer for handling image uploads
- **Authentication**: JWT-based secure authentication
- **Deployment**: Hosted on Heroku/Vercel for accessibility

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Car-Management-App.git
   cd Car-Management-App

2. **Install Dependencies:
   ```bash
      npm install
3. **Run the Server:
   ```bash
      npm start
4. **Access the Application:
   ```bash
   http://localhost:5000

## API Endpoints

- **POST /api/auth/signup**: Register a new user
- **POST /api/auth/login**: Login user and retrieve JWT
- **POST /api/cars**: Create a new car entry (requires authentication)
- **GET /api/cars**: Get all car entries (requires authentication)
- **PUT /api/cars/:id**: Update a car entry by ID (requires authentication)
- **DELETE /api/cars/:id**: Delete a car entry by ID.

## Usage with Postman

- **Set Authorization**: Use Bearer Token in the headers for protected routes.
- **Image Upload**: Use form-data in the body to upload images (key: images).
