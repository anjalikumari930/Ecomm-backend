# E-Commerce Server Backend

This is the backend server for an e-commerce application built using Node.js and Express.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Features

### 1. Online Catalog and Product Listings:

- Display products and services with detailed descriptions, images, and prices.
- Organize items into categories and subcategories for easy navigation.

### 2. Shopping Cart:

- Allow users to add and manage multiple products before proceeding to checkout.
- Calculate and display the total order value, including taxes and shipping costs.

### 3. User Accounts and Profiles:

- Enable customers to create accounts for a personalized shopping experience.
- Store order history, shipping addresses, and payment preferences securely.

### 4. Secure Payment Options:

- Provide various payment methods, such as credit cards, digital wallets, and bank transfers.
- Implement secure payment gateways to protect sensitive information.

### 5. Order Management:

- Allow users to track the status of their orders, from processing to shipment and delivery.
- Send email notifications for order confirmation, shipping updates, and delivery confirmation.

### 6. Search and Filters:

- Implement search functionality for users to find products quickly.
- Offer advanced filtering options to refine search results by category, price range, brand, etc.

### 7. Responsive Design:

- Ensure the website is accessible and user-friendly across different devices, including desktops, tablets, and smartphones.

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB installed and running

### Installation

1. Clone the repository:

cd your-ecommerce-backend
npm install

Add the below data with their key in .env file in the root folder

PORT=5000
MONGODB_URI=mongodb://localhost:27017/your_database_name
JWT_SECRET=your_secret_key
DEV_MODE=development

BRAINTREE_MERCHANT_ID =
BRAINTREE_PUBLIC_KEY=
BRAINTREE_PRIVATE_KEY=

npm start OR node server

## API Documentation

Explore our API endpoints using [Postman](https://documenter.getpostman.com/view/32458912/2s9YsT6oQY).

API Publisded link: https://documenter.getpostman.com/view/32458912/2s9YsT6oQY
