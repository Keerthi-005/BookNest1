BookNest: Where Stories Nestle

A full-stack book store application built with the MERN stack.
Team Details:

Team ID: LTVIP2026TMIDS24289
Team Size: 4
Team Leader: Keerthi Mekala
Team Member: Adil Mohammed
Team Member: Vasanth Metla
Team Member: Rahamtulla Shaik

Features:

User authentication (register/login)
Browse and search books
Add books to wishlist
Order books with buyer details
Seller dashboard to manage books and orders
Admin dashboard to manage users, sellers, and books

Tech Stack
Frontend: React.js, React Router, Bootstrap, Axios
Backend: Node.js, Express.js, MongoDB, Mongoose
Authentication: bcrypt for password hashing
Setup Instructions
Prerequisites

Node.js (v14 or higher)
MongoDB (local or MongoDB Atlas)
npm or yarn

Backend Setup

Navigate to the Backend directory:

cd Backend

Install dependencies:

npm install

Start the server:

npm start
The backend server will run on http://localhost:4000
Frontend Setup

Navigate to the Frontend directory:

cd Frontend

Install dependencies:

npm install

Start the development server:

npm run dev
The frontend will run on http://localhost:5173
API Endpoints
Users

POST /signup - Register new user
POST /login - User login

Sellers:

POST /ssignup - Register new seller
POST /slogin - Seller login
GET /getitem/:userId - Get seller's books
DELETE /itemdelete/:id - Delete book

Admin:

POST /asignup - Register admin
POST /alogin - Admin login
GET /users - Get all users
GET /sellers - Get all sellers
DELETE /userdelete/:id - Delete user
DELETE /sellerdelete/:id - Delete seller

Books:

POST /items - Add new book
GET /item - Get all books
GET /item/:id - Get single book
DELETE /useritemdelete/:id - Admin delete book

Orders:

POST /userorder - Place order
GET /getorders/:userId - Get user orders
GET /getsellerorders/:sellerId - Get seller orders
GET /orders - Get all orders (admin)

Wishlist:

POST /wishlist/add - Add to wishlist
GET /wishlist/:userId - Get user wishlist
POST /wishlist/remove - Remove from wishlist

Project Structure
Book-Store/
├── Frontend/          # React frontend
│   └── src/
│       ├── User/      # User pages
│       ├── Seller/    # Seller pages
│       ├── Admin/     # Admin pages
│       └── Components/
└── Backend/           # Express backend
    ├── db/            # Database config & models
    └── server.js      # Entry point
Usage

Register as a User, Seller, or Admin
Users can browse books, add to wishlist, and place orders
Sellers can add books and manage their orders
Admin can manage all users, sellers, and books
