# Full-Stack E-Commerce Project: A Comprehensive Overview

## Introduction
Embarking on a hands-on journey, this project focuses on designing and building an advanced e-commerce platform leveraging the MERN stack (MongoDB, Express.js, React.js, Node.js). Through this process, I aim to deepen my expertise in crafting dynamic, secure, and scalable web applications.

---

## Milestone 1: Initial Planning and Setup
### Objectives
This phase provided a foundation for:
- Structuring a MERN stack application.
- Familiarizing with core e-commerce functionalities.
- Preparing resources and tools for streamlined development.

### Key Features
- **Technology Focus**: Leveraging the MERN stack for seamless interaction between client-side and server-side technologies.
- **API Development**: Modular, maintainable APIs for user management, product cataloging, and transactions.
- **Authentication Mechanisms**: Secure user login and data protection.
- **Database Schema Design**: Practical, scalable data models.
- **Frontend UI/UX**: Intuitive interface using React.js.

---

## Milestone 2: Initial Application Setup
### Goals
- Establish a boilerplate MERN application.
- Configure backend services and database connections.
- Install essential packages and dependencies.
- Structure the project for development efficiency.

### Accomplishments
- **Server Configuration**: Built a Node.js backend with Express.js.
- **Database Connection**: Integrated MongoDB for user and product data.
- **Environment Management**: Secured sensitive data using environment variables.
- **Authentication Implementation**: User session management and password hashing.
- **Frontend-Backend Integration**: Basic React components interacting with backend APIs.

---

## Milestone 3: Backend Architecture Design
### Highlights
- Developed foundational server architecture using Express.js.
- Implemented middleware for error handling and request parsing.
- Validated backend performance through test routes.
- Constructed user-focused models and controllers.

---

## Milestone 4: User Authentication System
### Deliverables
- **User Model**: Mongoose schema for user data.
- **Encryption**: Password hashing with bcrypt.
- **Controllers**: Endpoints for user registration and authentication.
- **Validation**: Input security to minimize risks.

---

## Milestone 5: User Signup Page Development
### Achievements
- Designed a visually appealing signup interface using React and Tailwind CSS.
- Enabled avatar uploads with streamlined file handling.
- Integrated password visibility toggles for improved usability.
- Implemented real-time feedback for API responses.

---

## Milestone 6: Backend Endpoint for Secure Signup
### Objectives
- Secure password encryption before storage.
- Safely store comprehensive user data.

---

## Milestone 7: Backend User Login Endpoint with Password Validation
### Features
1. **User Login Endpoint**: Validates user existence and credentials.
2. **Password Encryption & Comparison**: Bcrypt for secure password handling.
3. **Secure Authentication Process**: Ensures safe user logins.

### Tech Stack
- **Node.js/Express**: Backend API
- **MongoDB**: Data storage
- **Bcrypt**: Password security

---

## Milestone 8: Product Card Component & Homepage Layout
### Features
- **Reusable Card Component**: Displays product details dynamically.
- **Dynamic Data Rendering**: Uses array mapping.
- **Responsive Homepage Design**: Grid layout for product showcase.

---

## Milestone 9: Product Input Form
### Features
- User-friendly form for product details.
- Supports multiple image uploads.
- Basic validation for accurate inputs.

---

## Milestone 10: Product Schema and Endpoint Creation
### Features
- Defined a Mongoose schema for products.
- Implemented validation for product data.
- Created a POST endpoint for product storage.

---

## Milestone 11: Dynamic Home Page with Product Data
### Features
- Backend API to fetch product data from MongoDB.
- Dynamic rendering of product listings using React.

---

## Milestone 12: My Products Page
### Features
- API endpoint to retrieve user-specific products.
- Frontend function to fetch and display user-added products.
- Dynamic rendering using a reusable product card component.

---

## Milestone 13: Edit Uploaded Products
### Features
- **Edit Button**: Allows users to update product details.
- **Auto-fill Form**: Displays existing product data.
- **Update Endpoint**: Backend updates product details in MongoDB.

### Implementation Steps
1. Created an API endpoint for updating products.
2. Added an edit button to product cards.
3. Implemented a form to update product details.

---

## Milestone 14: Delete Functionality Implementation
### Features
- **DELETE Endpoint**: Removes products using their ID.
- **Frontend Integration**: Delete button on each product card.
- **Error Handling**: Ensures valid deletion requests.

### Next Steps
- Implement confirmation dialogs before deletion.
- Add notifications for status updates.
- Restrict delete permissions to authorized users.

---

## Getting Started 🚀
### Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the backend server:
   ```bash
   npm start
   ```
4. Test API endpoints using Postman:
   ```json
   {
     "email": "user@example.com",
     "password": "password123"
   }
   ```

---

## Submission Progress 🚩
- **Code Repository**: [GitHub Link](#)
- **README**: Updated with milestone details.
- **Project Status**: Ongoing with upcoming enhancements.

This phased approach ensures steady progression while cementing critical full-stack development concepts and best practices.

Milestone 15: Navigation Component 📝
1. Create a New Nav Component
The Nav component should contain links to the following pages:
Home
My Products
Add Product
Cart
2. Make the Navbar Responsive
Ensure the Nav component is fully responsive across all screen sizes.
Use CSS media queries or a framework like Tailwind CSS or Bootstrap for styling.
3. Add the Nav Component to All Pages
Include the Nav component in all pages of the application.
Implement smooth navigation to ensure a seamless user experience.
Learning Outcomes
Understand to create a navigation bar in a web application.
Learn to implement responsive design for better usability.
Enhance your skills in linking multiple pages for smooth navigation.
Milestone 16 - Product Info Page
will create a product info page that displays all the product data, allows users to choose the quantity, and includes an "Add to Cart" button.
Learning Goals 🎯
By the end of this milestone:

How to create a new page to display each product.
How to add a quantity selector and an "Add to Cart" button.
Steps for Milestone 16 📝
Create a new page that displays all the product data.
Implement a quantity selector for each product.
Add an "Add to Cart" button to allow users to add products with the selected quantity.
Milestone 17: Cart Functionality
Overview
In this milestone,work on implementing cart functionality. The goal is to store product details in a user's cart and create an endpoint to receive and store these details in the database.

Steps for Milestone 17 📝
1. Edit the User Schema to Store Cart Products
Modify the user schema to include a field that will hold product details in the cart.
2. Write the Cart Schema to Store Products
Create a new schema for the cart that can store product details such as product ID, quantity, and other necessary attributes.
3. Write an Endpoint to Receive and Store Product Details in the Cart
Create a new endpoint that will receive product details from the frontend and store them in the database, specifically in the cart.
Milestone 18: Cart Functionality - Backend Endpoints
Overview
In this milestone, work on backend functionality for the cart. The goal is to create endpoints that handle requests from the cart page and retrieve product details for a user’s cart.

By the End of This Milestone,
Create an endpoint to receive requests from the cart page.
Create a backend endpoint to fetch all the products inside the cart based on the user's email.
Steps for Milestone 18 📝
1. Create a Backend Endpoint for Cart Page
Implement an endpoint that will receive requests from the frontend (cart page) and store/update products in the user's cart.
2. Write an Endpoint to Get Products Inside Cart for a User
Create a new endpoint that will fetch and return all the products inside the cart for a specific user, identified by their email.
🛒 Cart Functionality - Milestone 19
🎯 Learning Goals
Build a cart page that displays products inside the cart using the endpoint created in Milestone 18.
Implement an option to increase and decrease product quantity using + and - buttons.
Develop backend endpoints to handle quantity updates dynamically.
📝 Steps for Milestone 19
Create the Cart Page

Develop the frontend page to display products in the cart.
Add Quantity Controls

Implement + and - buttons for each product to allow users to adjust the quantity.
Set Up Backend Endpoints

Write API endpoints to increase and decrease product quantity based on user actions.
Milestone 20 - User Profile Page
Steps to Complete 📝
Backend:
Create an endpoint to send user data (including profile photo, name, email, and address).
Frontend:
Create a profile page to display user details.
Display the following information in one section:
Profile photo
Name
Email
In another section, display the user's address:
If an address exists, display it.
If no address is found, show: "No address found"
Add a button labeled "Add address" to allow users to add an address.
Notes:
Ensure proper API integration between frontend and backend.
Maintain a clean and responsive UI.
Handle cases where the user has no address data gracefully.

Milestone 21 ilestone 21! 🌟

Learning Goals 🎯
Create a frontend form that will take Take inputs for country, city, address

Steps for Milestone 21 📝
. Create an address form frontend page. . Create a state that will store the in . When clicking on 'Add Address' in the
