# Edgistify Assignment

## Introduction
This is an E-commerce app where users can buy products, it has a user authentication, product section, cart, and checkout functionality and only authenticated uses can proceed further.

## Project Type
Frontend | Backend | Fullstack

## Deplolyed App
Frontend: https://merry-malabi-cbb8ad.netlify.app/login
Backend: https://rb.gy/6lf8qu

## Directory Structure
Edgistify_Assignment/
├─ Backend/
├─ Frontend/
│  ├─ ...


## Features
List out the key features of your application.

- User Registration with express-validator
- User Login
- Product Section
- Cart Page
- Checkout Form


## Installation & Getting started
For Backend: 
```bash
cd Backend 
npm install
npm run dev
```
For Frontend: 
```bash
cd Frontend
cd my-app
npm install
npm run dev
```

## Usage
When you access the deployed frontend, you'll first encounter a registration form requiring your full name, a valid email, and a password of at least 8 characters, with backend validation handled by express-validator. After successful login, you're redirected to the product page, where you can browse and add items to your cart. The cart page displays your selected products, allowing you to review them before proceeding to checkout by entering your shipping address. The backend ensures product availability and quantity validation, providing appropriate error handling for a smooth shopping experience.


Include screenshots as necessary.

## Credentials
Provide user credentials for autheticated pages

## APIs Used
If your application relies on external APIs, document them and include any necessary links or references.

## API Endpoints
In case of Backend Applications provide a list of your API endpoints, methods, brief descriptions, and examples of request/response.

POST /api/user/register - user registeration
POST /api/user/login - user login





## Technology Stack
List and provide a brief overview of the technologies used in the project.
- Node.js
- Express.js
- MongoDB
- React
- Other libraries/modules
