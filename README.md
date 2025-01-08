# MERN Food Ordering App - Frontend

![Project Banner](https://i.ibb.co/5LH6zk2/screencapture-mern-food-ordering-app-frontend-g5ag-onrender-2025-01-08-23-06-44.png)

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Live Demo](#live-demo)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)
- [Contact](#contact)

## Project Description

The **MERN Food Ordering App Frontend** is a user-friendly interface built with React.js that allows users to browse, select, and order food from various restaurants. It is part of a full-stack MERN (MongoDB, Express, React, Node.js) application designed to provide a seamless food ordering experience. This frontend communicates with the backend API to handle user authentication, menu management, order processing, and real-time updates.

## Features

- **User Authentication**: Secure sign-up and login functionalities.
- **Restaurant Browsing**: Explore a variety of restaurants and their menus.
- **Real-time Order Tracking**: Monitor the status of your orders in real-time.
- **Cart Management**: Add, remove, and modify items in your cart effortlessly.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Search and Filter**: Easily find your favorite dishes or restaurants.
- **Payment Integration**: Secure payment gateway integration for hassle-free transactions.

## Technologies Used

- **Frontend**:
  - React.js
  - TypeScript
  - Redux for state management
  - React Router for navigation
  - Axios for API calls
  - Tailwind CSS for styling
  - Auth0 Authentication
  - Zod (Form Validation)
  - Radix UI Components
  
- **Tools**:
  - Git & GitHub for version control
  - Visual Studio Code as the code editor
  - ESLint & Prettier for code quality and formatting

## Installation Instructions

Follow these steps to set up the project locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Rohit8008/mern-food-ordering-app-frontend.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd mern-food-ordering-app-frontend
   ```

3. **Install Dependencies**

   Ensure you have [Node.js](https://nodejs.org/) installed. Then, install the required packages:

   ```bash
   npm install
   ```

4. **Configure Environment Variables**

   Create a `.env` file in the root directory and add the following variables:

   ```env
   VITE_API_BASE_URL=http://localhost:3000
   VITE_AUTH0_DOMAIN=your-auth0-domain
   VITE_AUTH0_CLIENT_ID=your-auth0-client-id
   VITE_AUTH0_CALLBACK_URL=http://localhost:5173/
   VITE_AUTH0_AUDIENCE=your-auth0-audience
   ```
    You can set up your Auth0 account [here](https://auth0.com/) and configure the domain, client ID, and audience in the `.env` file.


5. **Start the Development Server**

   ```bash
   npm run dev
   ```

   The app should now be running at `http://localhost:3000`.

## Usage

Once the application is up and running, you can:

1. **Sign Up or Log In**: Create a new account or log in with existing credentials.
2. **Browse Restaurants**: Explore different restaurants and view their menus.
3. **Add to Cart**: Select desired dishes and add them to your cart.
4. **Checkout**: Proceed to checkout, enter delivery details, and make a payment.
5. **Track Orders**: Monitor the status of your orders in real-time.


## Live Demo

You can view the live version of the project here:  
[**MERN Food Ordering App - Live Demo**](https://mern-food-ordering-app-frontend-g5ag.onrender.com/)

## Contribution Guidelines

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the Repository**

   Click the "Fork" button at the top-right corner of this page.

2. **Clone Your Fork**

   ```bash
   git clone https://github.com/your-username/mern-food-ordering-app-frontend.git
   ```

3. **Create a New Branch**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

4. **Make Your Changes**

   Commit your changes with clear and descriptive messages.

5. **Push to Your Fork**

   ```bash
   git push origin feature/YourFeatureName
   ```

6. **Create a Pull Request**

   Navigate to the original repository and click "Compare & pull request."

Please ensure your code adheres to the project's coding standards and includes necessary tests.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


## Contact

For any inquiries or feedback, please contact:

- **Rohit Mittal**
- **LinkedIn**: [linkedin.com/in/rohit8001](https://linkedin.com/in/rohit8001)
- **GitHub**: [Rohit8008](https://github.com/Rohit8008)

---

Happy Ordering! 🍔🍕🍣
