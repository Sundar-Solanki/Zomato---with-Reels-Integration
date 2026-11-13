# Zomato Clone - Backend

Express.js REST API for Zomato Clone.

## Features
- User & Food Partner Authentication (JWT + bcryptjs)
- Food Item & Reel Management
- Media uploads via Multer and ImageKit
- MongoDB database integration with Mongoose

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Configure `.env` using `.env.example` as a template:
   ```env
   JWT_SECRET=your_jwt_secret
   MONGODB_URI=your_mongodb_connection_string
   IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
   IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
   IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
   ```

3. Run server:
   ```bash
   npm start
   # or development mode:
   npm run dev
   ```

## Author

- **Sundar Solanki** ([sundar.solanki5555@gmail.com](mailto:sundar.solanki5555@gmail.com))

