# QueueCheck - Real-Time Queue Monitoring System

QueueCheck is a full-stack web application designed to help users avoid long waits by providing real-time queue information for local shops. Shop owners can register to manage their establishment's details and live queue status, while customers can search for shops and view up-to-the-minute wait times.

This project helps customers make informed decisions about where to go and when, saving them valuable time and improving their overall experience.

## Key Features

### For Customers (Users)
- **Search by Location:** Find all registered shops in a specific area.
- **View Shop Listings:** See a list of shops at the entered location.
- **Live Queue Details:** Click on a shop to view:
  - Current number of people in the queue.
  - The shop's status (Open/Closed).
  - An automatically calculated estimated wait time.
- **Simple Interface:** Clean and intuitive UI for a seamless user experience.

### For Shop Owners
- **Secure Registration & Login:** Create a dedicated account to manage your shop.
- **Shop Management Dashboard:**
  - **CRUD Operations:** Create, view, update, and delete your shop profile.
  - **Status Control:** Set your shop's name, location, and operating status (Open/Closed).
  - **Wait Time Configuration:** Input an estimated service time per customer to help calculate the wait time.
- **Live Queue Updates:** Easily update the current number of people in your queue to provide accurate information to customers.

## Tech Stack

### Backend
- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB
- **ODM:** Mongoose
- **Authentication:** JSON Web Tokens (JWT) for secure, stateless authentication.
- **Password Hashing:** bcryptjs
- **Middleware:** CORS, Custom middleware for role-based access control.

### Frontend
- **Structure:** HTML5
- **Styling:** CSS3
- **Logic:** Vanilla JavaScript (using Fetch API for asynchronous requests).

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later)
- [MongoDB](https://www.mongodb.com/try/download/community) installed and running on its default port (`27017`).

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/PraveenAladakatti/Queue_Check
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd Queue_Check
    ```

3.  **Install backend dependencies:**
    ```sh
    npm install
    ```

4.  **Create an environment file:**
    Create a `.env` file in the root of the project and add the following variables.
    ```
    PORT=5000
    JWT_SECRET=your_super_secret_key_here
    ```

5.  **Start the backend server:**
    ```sh
    npm start
    ```
    The server will be running on `http://localhost:5000`.

6.  **Launch the frontend:**
    Open the `index.html` or `login.html` file in your web browser to start using the application.


