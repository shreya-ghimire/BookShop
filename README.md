# Bookshop Application

This project is a Bookshop application built using React for the frontend, Node.js (Express) for the backend, and SQL for the database.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Features


- Browse and search for books
- View book details
- CRUD functionality
  


## Tech Stack

- **Frontend**: React, CSS
- **Backend**: Node.js, Express
- **Database**: SQL (MySQL)

## Setup Instructions

### Prerequisites

- Node.js (v14 or above)
- npm or yarn
- SQL Database (MySQL)

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/shreya-ghimire/bookshop.git
    cd bookshop
    ```

2. **Backend Setup:**

    - Navigate to the backend directory:
    
      ```sh
      cd backend
      ```
    
    - Install backend dependencies:
    
      ```sh
      npm install
      ```
    
    - Create a `.env` file in the backend directory and add your database configuration and other environment variables:
    
      ```
      DB_HOST=your_db_host
      DB_USER=your_db_user
      DB_PASSWORD=your_db_password
      DB_NAME=your_db_name
      JWT_SECRET=your_jwt_secret
      ```

    - Run the backend server:
    
      ```sh
      npm start
      ```

3. **Frontend Setup:**

    - Navigate to the frontend directory:
    
      ```sh
      cd ../frontend
      ```
    
    - Install frontend dependencies:
    
      ```sh
      npm install
      ```
    
    - Start the frontend development server:
    
      ```sh
      npm start
      ```

    The application should now be running and accessible at `http://localhost:3000`.
