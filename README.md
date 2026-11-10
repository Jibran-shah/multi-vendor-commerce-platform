
# Multi-Vendor Commerce Platform

A full-stack MERN platform that combines multi-vendor e-commerce and service marketplace functionality, allowing customers to purchase products, discover services, and connect with sellers and service providers through a single platform.

## Features

- User authentication and authorization
- Customer, product seller, and service provider accounts
- Product listing and management
- Service listing and management
- Product categories and service discovery
- Shopping cart and order management
- Service booking and management
- Seller and service provider profiles
- Real-time messaging and communication
- Secure payment integration
- Responsive user interface

## Tech Stack

**Frontend**
- React.js
- Material UI
- React Router
- Redux Toolkit
- TanStack Query

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- REST APIs

**Real-Time Communication**
- Socket.IO
- Apache Kafka
- Redis

**Other Tools & Technologies**
- JWT Authentication
- Zod
- Safepay Payment Gateway
- Git & GitHub

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Jibran-shah/multi-vendor-commerce-platform.git
cd multi-vendor-commerce-platform
```

### 2. Install Dependencies

Install backend dependencies:

```bash
cd backend
npm install
```

Install frontend dependencies:

```bash
cd ../frontend
npm install
```

### 3. Configure Environment Variables

Create `.env` files in the required directories.

Refer to `.env.example` files for the required environment variables and configuration.

### 4. Run the Application

Start the backend:

```bash
cd backend
npm run dev
```

Start the frontend in a separate terminal:

```bash
cd frontend
npm run dev
```

## Project Structure

```text
multi-vendor-commerce-platform/
├── backend/
│   ├── src/
│   └── package.json
├── frontend/
│   ├── src/
│   └── package.json
└── README.md
```

## License & Copyright

Copyright (c) 2026 Jibran Shah.

All Rights Reserved.

This project is provided for viewing and educational purposes only. No permission is granted to copy, modify, distribute, or use this code without prior written permission from the copyright owner.
