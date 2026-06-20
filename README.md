# 📚 Jarir Bookstore Management Backend

A scalable and production-ready bookstore management REST API built with Node.js, Express.js, MongoDB, Mongoose, and JWT Authentication. This backend powers the Jarir Bookstore Management System, providing secure APIs for managing books, inventory, customers, orders, users, and reports.

---

## 🚀 Live Features

### 🔐 Authentication & Authorization

- User Registration
- User Login
- JWT Authentication
- Password Hashing with bcryptjs
- Role-Based Access Control (Admin, Manager, Staff)
- Protected Routes

### 👥 User Management

- Create Users
- Update User Information
- Delete Users
- View User Profiles
- Manage User Roles

### 📚 Book Management

- Add New Books
- Update Book Details
- Delete Books
- Search Books
- Filter Books
- Book Categories

### 📦 Inventory Management

- Track Stock Levels
- Update Inventory
- Low Stock Monitoring
- Inventory Reports

### 🛒 Order Management

- Create Orders
- Update Order Status
- Order History
- Customer Purchase Tracking

### 👤 Customer Management

- Add Customers
- Update Customer Information
- Customer Order History
- Customer Analytics

### 📊 Reporting & Analytics

- Sales Reports
- Inventory Reports
- Revenue Analytics
- Customer Insights

### ⚙️ System Features

- Global Error Handling
- Request Validation
- Pagination
- Search & Filtering
- Secure Environment Variables
- RESTful API Architecture

---

# 🛠️ Technology Stack

## Backend

- Node.js
- Express.js

## Database

- MongoDB
- Mongoose

## Authentication

- JWT (JSON Web Token)
- bcryptjs

## Validation

- Zod

## Security

- Helmet
- Express Rate Limit
- CORS
- MongoDB Sanitization

## Utilities

- dotenv
- cookie-parser
- multer

---

# 📂 Project Structure

```bash
jarir-bookstore-management-backend/
│
├── src/
│   │
│   ├── config/
│   │   ├── db.js
│   │   ├── env.js
│   │   └── cloudinary.js
│   │
│   ├── modules/
│   │   ├── auth/
│   │   ├── users/
│   │   ├── books/
│   │   ├── categories/
│   │   ├── inventory/
│   │   ├── customers/
│   │   ├── orders/
│   │   ├── reports/
│   │   └── settings/
│   │
│   ├── middleware/
│   │   ├── auth.js
│   │   ├── validateRequest.js
│   │   ├── notFound.js
│   │   └── globalErrorHandler.js
│   │
│   ├── utils/
│   │   ├── catchAsync.js
│   │   ├── sendResponse.js
│   │   ├── generateToken.js
│   │   └── paginationHelper.js
│   │
│   ├── constants/
│   ├── helpers/
│   ├── app.js
│   └── server.js
│
├── uploads/
├── logs/
├── .env
├── .gitignore
├── package.json
├── README.md
```
