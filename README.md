# ICare - Optical Care Management System

## Project Overview
ICare is a full-stack web application for managing optical care services, appointments, and products. The system includes features for managing prescriptions, digital library, appointments, and optical products.

## Tech Stack
- Frontend: React.js
- Backend: Node.js/Express.js
- Database: MongoDB
- Authentication: JWT
- File Upload: Cloudinary
- Email Service: Mailgun

## Project Structure
```
ICare/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── utils.js
│   └── .env
└── frontend/
    ├── public/
    ├── src/
    ├── build/
    └── package.json
```

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm or yarn

### Installation
1. Clone the repository
```sh
git clone [repository-url]
cd ICare
```

2. Install Backend Dependencies
```sh
cd backend
npm install
```

3. Install Frontend Dependencies
```sh
cd frontend
npm install
```

## Environment Setup
Create a `.env` file in the backend directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
MAILGUN_API_KEY=your_mailgun_api_key
MAILGUN_DOMAIN=your_mailgun_domain
```

## Running the Application
1. Start the Backend Server
```sh
cd backend
npm start
```
The server will run on http://localhost:5000

2. Start the Frontend Development Server
```sh
cd frontend
npm start
```
The application will open in your default browser at http://localhost:3000

## Building for Production
To create a production build of the frontend:
```sh
cd frontend
npm run build
```

## Features
- User Authentication and Authorization
- Appointment Management
- Prescription Management
- Digital Library
- Product Catalog
- Order Management
- Optometrist Dashboard
- Customer Support Ticketing System

## API Endpoints
- `/api/users` - User management
- `/api/appointments` - Appointment management
- `/api/prescriptions` - Prescription management
- `/api/products` - Product management
- `/api/orders` - Order management
- `/api/library` - Digital library management
- `/api/optometrists` - Optometrist management
- `/api/tickets` - Support ticket management

