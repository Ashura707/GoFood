# GoFood

GoFood is a food ordering application built using the MERN stack (MongoDB, Express, React, Node.js). The application allows users to browse a variety of food items, place orders, and manage their orders seamlessly. This README provides an overview of the project, setup instructions, and usage guidelines.

## Features

- User authentication and authorization
- Browse and search food items
- Add items to cart
- Place orders
- View order history
- Admin dashboard to manage food items and orders
- Responsive design for mobile and desktop users

## Technologies Used

- **Frontend:** React, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **State Management:** Redux
- **Authentication:** JWT (JSON Web Tokens)
- **Styling:** Bootstrap

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- Node.js (v14.x or higher)
- npm (v6.x or higher) or yarn (v1.x or higher)
- MongoDB (v4.x or higher)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ashura707/GoFood.git
   ```

2. Install dependencies for both the client and server:
   ```bash
   cd gofood
   npm install
   cd backend
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `server` directory.
   - Add the following environment variables to the `.env` file:
     ```env
     PORT=5000
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

## Running the Application

1. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

2. Start the frontend development server:
   ```bash
   cd gofood
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Folder Structure


  - **public**: Public assets and the main HTML file.
  - **src**: Source code for the React application.
    - **components**: Reusable React components.
      - **images**: Folder containing image assets.
      - **card.js**: Component for displaying food items in a card format.
      - **carousel.js**: Component for the image carousel.
      - **contextreducer.js**: Reducer for managing global state.
      - **footer.js**: Footer component.
      - **navbar.js**: Navigation bar component.
    - **screens**: Page components representing different routes.
      - **cart.js**: Cart page component.
      - **home.js**: Home page component.
      - **login.js**: Login page component.
      - **myorder.js**: My Orders page component.
      - **signup.js**: Signup page component.
    - **redux**: Redux setup for state management.
    - **styles**: Bootstrap CSS styles.
    - **utils**: Utility functions and constants.
    
- **server**: Contains the Node.js backend code.
  - **controllers**: Functions to handle requests and responses.
  - **models**: Mongoose models for MongoDB collections.
  - **routes**: Express routes for the API endpoints.
  - **middleware**: Custom middleware functions.
  - **config**: Configuration files and environment setup.

## Usage

- **User Registration and Login:**
  - Users can sign up and log in using their email and password.
  - Authentication is handled using JWT.

- **Browsing Food Items:**
  - Users can browse the available food items on the home page.
  - Search functionality is provided to find specific items.

- **Adding to Cart and Placing Orders:**
  - Users can add items to their cart.
  - Orders can be placed from the cart page.
  - Order history can be viewed from the user's profile.

- **Admin Dashboard:**
  - Admin users can log in to access the admin dashboard.
  - Admins can manage food items and view all orders.

## Contributing

We welcome contributions to improve GoFood! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.


## Contact

If you have any questions or suggestions, feel free to reach out to at rohitcr7mishra@gmail.com

---

Thank you for using GoFood! We hope you enjoy it. Happy ordering!