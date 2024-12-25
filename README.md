**Name:** J SRIKANTH

**Company:** CODTECH IT SOLUTIONS

**ID:** CT08EJV

**Domain:** Full Stack Web Development

**Duration:** December to January 2025

**Mentor:** N. Santhosh

## Overview of the project

### Project: Basic e-commerce platform

This project implements a basic e-commerce platform featuring user authentication, product listings, and a shopping cart. It uses a full-stack approach with a React frontend and an Express.js backend integrated with a MongoDB database. The platform also includes basic functionality for handling payments, with a placeholder for payment gateway integration.

## Core Features

**1. User Authentication and Authorization**

**Registration:** Users can create an account by providing a username and password.

**Login:** Users log in with their credentials to receive a JSON Web Token (JWT).

**Authorization Middleware:** Protects certain routes to ensure only authenticated users can access them.

**2. Product Listings**
Backend provides endpoints to manage products (GET and POST operations).
Products have attributes such as name, price, description, and image.
Frontend fetches the list of products from the backend and displays them in a user-friendly format.

**3. Shopping Cart**
Users can add products to a shopping cart.
Displays cart contents in real-time on the frontend.
Includes a checkout button, which sends the cart data to a placeholder API for payment processing.

**4. Payment Gateway Integration**
Simulates payment functionality with a placeholder API.
Designed for integration with a real payment gateway, such as Stripe, PayPal, or Razorpay.

## Tech Stack
**Frontend:**

React: Handles the user interface and state management for the shopping cart and product display.

**Backend:**

Express.js: Manages API endpoints for authentication, product management, and other business logic.

JWT: Provides secure authentication and session management.

Bcrypt: Ensures secure password hashing.

**Database:**

MongoDB: Stores user data and product details.

Other Libraries and Tools:

Axios: Handles HTTP requests in the frontend.

Cors: Enables cross-origin requests between frontend and backend.

Body-Parser: Parses incoming request bodies in the backend.

## Future Enhancements

Enhanced Payment Integration: Replace the placeholder payment API with a real payment gateway like Stripe or PayPal.

Admin Dashboard: Add an interface for admins to manage products and view user activities.

User Profiles: Allow users to view order history and manage their account.

Search and Filters: Enable search functionality and filtering of products.

Deployment: Host the app on platforms like AWS, Heroku, or Vercel for production use.
