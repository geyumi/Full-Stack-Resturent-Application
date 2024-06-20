
# Restaurant Reservation App

## Overview

The Restaurant Reservation App is a full-stack web application designed to allow users to book reservations at a restaurant. It is built using the MERN stack, incorporating MongoDB for the database, Express and Node.js for the backend server, and React for the frontend interface.

## Features

- **Home Page**: Provides an overview of the restaurant and links to other sections.
- **About Us**: Information about the restaurant.
- **Our Services**: Details on the services provided by the restaurant.
- **Book a Reservation**: A form to make new reservations.
- **Menus**: A list of the restaurant’s menu items.
- **Team**: Information about the restaurant's team members.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Styling**: CSS

## Setup and Installation

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB instance running (can be local or MongoDB Atlas).
- A code editor (VSCode, Sublime Text, etc.).

### Backend Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/restaurant-reservation-app.git
   cd restaurant-reservation-app/backend
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Configure Environment Variables**

   Create a `.env` file in the backend directory with the following variables:

   ```plaintext
   MONGODB_URI=<your_mongodb_connection_string>
   PORT=5000
   ```

4. **Start the Server**

   ```bash
   npm start
   ```

### Frontend Setup

1. **Navigate to the Frontend Directory**

   ```bash
   cd ../frontend
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Development Server**

   ```bash
   npm start
   ```

   This will start the React development server, usually on `http://localhost:3000`.

## Project Structure

### Backend

- **/models**: Contains Mongoose schemas.
- **/routes**: API routes.
- **/controllers**: Business logic for handling requests.
- **/config**: Configuration files (e.g., MongoDB connection).
- **server.js**: Entry point for the server.

### Frontend

- **/src**: Main source directory.
  - **/components**: React components.
  - **/pages**: Page components.
  - **/services**: API service calls.
  - **App.js**: Main application component.
  - **index.js**: Entry point for React.

## API Endpoints

### Reservation Endpoints

- **POST /api/reservations**: Create a new reservation.

## Usage

- **Navigate to `http://localhost:5173`** in your browser to view the application.
- Use the navigation menu to explore different sections of the restaurant.
