# Karoo (E-Commerce Web Application) [(Video Demo)](https://drive.google.com/drive/folders/1sQtSXmm1z4RC78WRkljfrWyqBEEXfhci?usp=drive_link)


## Overview

Karoo is a full-stack e-commerce web application developed using the MERN stack (MongoDB, Express, React, Node.js). This final iteration builds upon previous versions by integrating a complete client-server architecture, persistent database storage, user authentication, and real-time communication.

The application allows users to browse products, search items, manage a shopping cart, and interact with a dynamic and responsive user interface. Each user has their own account and personalized data, enabled through authentication and database integration.

To meet the project requirements, the application includes:

A React frontend with a user-friendly and responsive UI
A Node.js + Express backend with RESTful API routes
A MongoDB database for persistent data storage
User authentication allowing multiple users to log in and manage their own data
Real-time communication using Socket.io
A UI designed using Nielsen usability principles to ensure usability and accessibility

This project demonstrates a complete modern web application workflow from frontend design to backend API development and database management.

## Documentation

How to Run the Project:

1. Clone or download the project repository.
2. Navigate to the backend folder and install dependencies:
```
npm install
npm install mongoose
```
3. Navigate to the frontend folder and install dependencies:
```
npm install
npm install react-router-dom
```
4. Start the application:
Backend: `npm run start`
Frontend: `npm run dev`
5. Open your browser and go to: http://localhost:5173

## Routes & API:

### Frontend Routes
- `/` or `/home` → Home Page
- `/about` → About Page
- `/electronics` → Electronic Products Page
- `/beauty` → Beauty Products Page
- `/apparel` → Apparel Products Page
- `/best-seller` → Best Sellers Products Page
- `/cart` → Cart Page
- `/faq` → Frequently Asked Questions Page
- `/privacy` → Privacy Policy Page
- `/terms` → Terms and Conditions Page
- `/shipping` → Shipping and Returns Page
- `/staff` → Staff/Admin Page
- `/underconstruction` → Future Features

### Backend API

| Method | Endpoint                          | Description                             | Status Codes                        |
| ------ | --------------------------------- | --------------------------------------- | ----------------------------------- |
| GET    | /api/products                     | Retrieve the list of available products | 200 OK, 404 Not Found               |
| GET    | /api/products/beauty              | Retrieve the list of beauty products    | 200 OK, 404 Not Found               |
| GET    | /api/products/apparel             | Retrieve the list of apparel products   | 200 OK, 404 Not Found               |
| GET    | /api/products/electronics         | Retrieve the list of electronic products| 200 OK, 404 Not Found               |
| GET    | /api/products/random              | Retrieve the list of random products    | 200 OK, 404 Not Found               |
| GET    | /api/products/search              | Retrieve a specific product by name     | 200 OK, 404 Not Found, 400 No Input |
| GET    | /api/products/:pid                | Retrieve a specific product by PID      | 200 OK, 404 Not Found               |
| GET    | /api/cart/:email                  | Retrieve a specific cart by user email  | 200 OK, 500 Server Error            |
| POST   | /api/products                     | Add a new product to the list           | 201 Created, 400 Bad Request        |
| POST   | /api/products/electronic          | Add a new electronic product to the list| 201 Created, 400 Bad Request        |
| POST   | /api/products/apparel             | Add a new apparel product to the list   | 201 Created, 400 Bad Request        |
| POST   | /api/products/beauty              | Add a new beauty product to the list    | 201 Created, 400 Bad Request        |
| POST   | /api/cart/add                     | Add a product to a user's cart          | 200 OK, 500 Server Error            |
| POST   | /api/cart/remove                  | Remove a product from a user's cart     | 200 OK, 500 Server Error            |
| PATCH  | /api/products/pid/:pid            | Update a product's price                | 200 OK                              |
| PATCH  | /api/products/:pid/cart           | Update a product's in cart status       | 200 OK, 500 Server Error            |
| DELETE | /api/products/pid/:pid            | Delete a product using its unique ID    | 204 OK, 500 Server Error            |

These endpoints enable communication between the client-side pages and the server, demonstrating proper use of HTTP methods and RESTful design principles.

### Key Features
- Full MERN stack implementation
- RESTful API design
- MongoDB database integration
- User authentication system
- Individual user data handling
- Shopping cart functionality
- Real-time communication (Socket.io)
- Responsive and intuitive UI

### Image Demo
<img width="1434" height="900" alt="Screenshot 2026-06-03 at 5 53 44 PM" src="https://github.com/user-attachments/assets/e64a1535-ef85-4384-bc33-8fd0ba390b92" />
<img width="1440" height="900" alt="Screenshot 2026-06-03 at 5 54 03 PM" src="https://github.com/user-attachments/assets/3289f56f-abc9-4db4-a7e6-5f157c18a7c9" />
<img width="1440" height="900" alt="Screenshot 2026-06-03 at 5 54 24 PM" src="https://github.com/user-attachments/assets/3f0b78c4-7c29-46f3-a8d1-4c9787015de0" />
<img width="1440" height="900" alt="Screenshot 2026-06-03 at 5 54 46 PM" src="https://github.com/user-attachments/assets/154b8e00-9385-4ae2-ad72-eff6c8244931" /><img width="1440" height="900" alt="Screenshot 2026-06-03 at 5 55 20 PM" src="https://github.com/user-attachments/assets/70e1b4a0-e648-4258-9c28-d8859913f901" />
<img width="1440" height="900" alt="Screenshot 2026-06-03 at 5 55 41 PM" src="https://github.com/user-attachments/assets/c6766749-021a-4c82-a177-6f02961323cf" />


