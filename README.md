# Food Delivery App
<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/7778ad14-3ce4-4d11-a6ce-9386fd544828" />

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

### Frontend
![Frontend Screenshot](<img width="1901" height="868" alt="Screenshot 2025-11-29 011135" src="https://github.com/user-attachments/assets/6882c3dd-a36f-4e4f-be91-e523d18cd384" />,  
<img width="1900" height="868" alt="Screenshot 2025-11-29 011840" src="https://github.com/user-attachments/assets/53611c44-6258-4009-8f40-a0e629904e0f" /> ,    
<img width="1885" height="853" alt="Screenshot 2025-11-29 011850" src="https://github.com/user-attachments/assets/5c5f82e5-5ce7-445b-9ca9-a90e7200bb24" />
)

### Admin Panel
![Admin Panel Screenshot](<img width="1878" height="866" alt="Screenshot 2025-11-29 011656" src="https://github.com/user-attachments/assets/4676e08c-2cbf-4990-8366-7d21baa19148" />,    
<img width="1883" height="826" alt="Screenshot 2025-11-29 012013" src="https://github.com/user-attachments/assets/2bf0e86b-5631-4276-8f93-229c06e9845b" /> ,     
<img width="1889" height="856" alt="Screenshot 2025-11-29 012024" src="https://github.com/user-attachments/assets/69fb33cd-b97c-4c4c-ad61-da17ce202808" />
)

### Database Schema
![Database Schema](<img width="1897" height="849" alt="Screenshot 2025-11-29 012329" src="https://github.com/user-attachments/assets/d6276f7d-6dec-48cc-b7b1-619064504dac" />
<img width="1897" height="855" alt="Screenshot 2025-11-29 012346" src="https://github.com/user-attachments/assets/449b2060-c1a8-466c-9854-fb22c73aa5ed" />
<img width="1885" height="837" alt="Screenshot 2025-11-29 012358" src="https://github.com/user-attachments/assets/e9f8639c-b913-4091-aa58-e734c998d8f1" />
)

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
