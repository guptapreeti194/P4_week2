# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

                                         **Custom E-Commerce Platform with MERN Stack**
##Custom E-Commerce Platform with MERN Stack

This is a fully functional custom e-commerce platform built with the MERN stack (MongoDB, Express.js, React, Node.js). Users can browse products, add items to the cart, and make payments securely.

## Features

- User authentication (sign up, log in, log out)
- Product browsing with category filters
- Shopping cart functionality
- Admin panel for product management
- Payment integration with Stripe/PayPal

## Tech Stack

- **Frontend**: React, Redux, TailwindCSS
- **Backend**: Node.js, Express.js, MongoDB
- **Other**: JWT for authentication, Stripe/PayPal for payment processing

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/guptapreeti194/P4_week2.git
    ```
2. Install dependencies for the backend:
    ```bash
    cd backend
    npm install
    ```
3. Create a `.env` file in the backend directory with the following variables:
    - `MONGO_URI=your-mongo-db-uri`
    - `JWT_SECRET=your-secret-key`
4. Start the backend server:
    ```bash
    npm run dev
    ```
5. Install dependencies for the frontend:
    ```bash
    cd frontend
    npm install
    ```
6. Start the frontend:
    ```bash
    npm run dev
    ```

## Usage

Once the backend and frontend are running, you can access the e-commerce platform at `http://localhost:5173`. You can browse products, add them to the cart, sign up, and complete a purchase.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and create a pull request. Please make sure to follow the existing coding standards and add tests for any new features.

## Acknowledgements

- React, Express, Node.js, MongoDB
- Stripe/PayPal for payment processing
- TailwindCSS for styling
