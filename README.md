# BookNest: Where Stories Nestle

A full-stack book store application built with the MERN stack.

## Team Details

| | |
|---|---|
| **Team ID** | LTVIP2026TMIDS24289 |
| **Team Size** | 4 |
| **Team Leader** | Keerthi Mekala |
| **Team Member** | Adil Mohammed |
| **Team Member** | Vasanth Metla |
| **Team Member** | Rahamtulla Shaik |

## Features

- User authentication (register/login)
- Browse and search books
- Add books to wishlist
- Order books with buyer details
- Seller dashboard to manage books and orders
- Admin dashboard to manage users, sellers, and books

## Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React.js, React Router, Bootstrap, Axios |
| **Backend** | Node.js, Express.js, MongoDB, Mongoose |
| **Authentication** | bcrypt for password hashing |

## Setup Instructions

### Backend Setup

1. Navigate to the Backend directory:
   `cd Backend`
2. Install dependencies:
   `npm install`
3. Start the server:
   `npm start`

The backend runs on **http://localhost:4000**

### Frontend Setup

1. Navigate to the Frontend directory:
   `cd Frontend`
2. Install dependencies:
   `npm install`
3. Start the development server:
   `npm run dev`

The frontend runs on **http://localhost:5173**

## Project Structure
```
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
```

## Usage

1. Register as a **User**, **Seller**, or **Admin**
2. Users can browse books, add to wishlist, and place orders
3. Sellers can add books and manage their orders
4. Admin can manage all users, sellers, and books
