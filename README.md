# Rentify

Rentify is a web application designed for renting and selling homes. It features a frontend built with Vite and React, and a backend powered by Node.js and Express. MongoDB is used for data storage.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Overview

Rentify provides a platform for users to list, browse, and manage rental and sale properties. Users can search for homes, view details, and contact the property owner or agent directly through the application.

## Features

- User authentication and authorization
- Property listing for renting and selling
- Search and filter properties
- Detailed property view with images and descriptions
- Contact property owners or agents
- User dashboard for managing listings and inquiries

## Installation

### Prerequisites

- Node.js (version 14 or higher)
- MongoDB

### Backend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/rentify.git
   cd rentify
   ```

2. Navigate to the backend directory:

   ```bash
   cd api
   ```

3. Install backend dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the `api` directory and configure the environment variables:

   ```plaintext
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. Start the backend server:

   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd ../client
   ```

2. Install frontend dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the `client` directory and configure the environment variables:

   ```plaintext
   VITE_API_URL=http://localhost:5173
   ```

4. Start the frontend development server:

   ```bash
   npm run dev
   ```

## Usage

1. Ensure MongoDB is running.
2. Start the backend server (as shown in the Installation section).
3. Start the frontend development server (as shown in the Installation section).
4. Open your browser and navigate to `http://localhost:5173` to access the Rentify application.


## Technologies Used

- **Frontend:**
  - React
  - Vite
  - CSS (or any CSS framework/library you use)

- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - Mongoose (for MongoDB interactions)
