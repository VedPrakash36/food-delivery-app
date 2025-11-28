# Food Delivery App

A full-stack food delivery application built with React, Node.js, Express, and MongoDB. Features user authentication, food ordering, cart management, payment integration with Stripe, and an admin panel for managing orders and food items.

## Tech Stack

### Frontend
- React
- Vite
- Axios
- Stripe (for payments)

### Backend
- Node.js
- Express
- MongoDB (with Mongoose)
- JWT (authentication)
- Stripe (payments)
- Multer (file uploads)

### Admin Panel
- React
- Vite
- Axios

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- Stripe account (for payments)

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd food-del
   ```

2. Install dependencies for each part:

   **Backend:**
   ```
   cd backend
   npm install
   ```

   **Frontend:**
   ```
   cd ../frontend
   npm install
   ```

   **Admin:**
   ```
   cd ../admin
   npm install
   ```

3. Set up environment variables:
   - Create `.env` file in `backend/` directory
   - Add MongoDB URI, JWT secret, Stripe keys, etc.

## Usage

1. Start the backend server:
   ```
   cd backend
   npm run server
   ```

2. Start the frontend:
   ```
   cd frontend
   npm run dev
   ```

3. Start the admin panel:
   ```
   cd admin
   npm run dev
   ```

4. Access the app:
   - Frontend: http://localhost:5173
   - Admin: http://localhost:5174
   - Backend API: http://localhost:4000

## Features

- User registration and login
- Browse food items by category
- Add to cart and place orders
- Secure payment with Stripe
- Order tracking
- Admin panel for managing food items and orders
- Image uploads for food items

## API Endpoints

- `/api/user` - User authentication
- `/api/food` - Food items management
- `/api/cart` - Cart operations
- `/api/order` - Order management
- `/images` - Static image serving

## Contributing

Feel free to submit issues and pull requests.

## License

ISC
