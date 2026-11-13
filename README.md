# Zomato Clone

A full-stack food reels and discovery platform built with React, Node.js, Express, and MongoDB.

## Features

- **Food Reels & Feed**: Short video reels showcasing delicious dishes from food partners.
- **User Authentication**: Secure registration and login for users and food partners.
- **Food Partner Portal**: Create and upload food dishes, reels, and manage partner profiles.
- **Save & Bookmark**: Save favorite dishes and access them anytime.
- **Media Storage**: Seamless video and image management using ImageKit.

---

## Tech Stack

### Frontend
- **Framework**: React 19 + Vite
- **Routing**: React Router DOM
- **HTTP Client**: Axios
- **Styling**: Modern CSS

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JWT (JSON Web Tokens) & bcryptjs
- **Media Uploads**: Multer & ImageKit

---

## Getting Started

### Prerequisites
- Node.js (v18 or newer recommended)
- MongoDB instance (local or MongoDB Atlas)
- ImageKit account credentials

### 1. Backend Setup

```bash
cd backend
npm install
```

Configure your environment variables in `backend/.env`:

```env
JWT_SECRET=your_jwt_secret
MONGODB_URI=your_mongodb_connection_string
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

Run the backend server:

```bash
npm start
# or for development with auto-reload:
npm run dev
```

The backend server runs on `http://localhost:3000`.

### 2. Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

The frontend application runs on `http://localhost:5173`.

---

## Project Structure

```text
zomato-clone/
├── backend/
│   ├── server.js          # Server entry point
│   ├── src/
│   │   ├── controllers/   # Request handlers
│   │   ├── models/        # Mongoose database schemas
│   │   ├── routes/        # Express API endpoints
│   │   ├── middlewares/   # Auth and upload middlewares
│   │   └── services/      # External integrations (e.g., ImageKit)
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Application views (Auth, Partner, Feed)
│   │   ├── routes/        # Routing configuration
│   │   └── styles/        # CSS styling
│   └── package.json
└── README.md
```

---

## Author

- **Sundar Solanki** ([sundar.solanki5555@gmail.com](mailto:sundar.solanki5555@gmail.com))

