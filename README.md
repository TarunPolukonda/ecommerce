# E-Commerce Web Application

## Overview
This e-commerce web application is designed to provide a seamless online shopping experience. It allows users to browse, select, and purchase items with ease. The project integrates multiple features such as user authentication, product management, payment gateway integration, and PDF invoice generation.

## Features
- **User Authentication**: Secure registration and login for customers and administrators.
- **Product Catalog**: Display of products with details such as price, description, and images.
- **Shopping Cart**: Add, update, or remove items from the cart.
- **Payment Integration**: Razorpay payment gateway for secure and smooth transactions.
- **Order Management**: Track user orders and generate invoices.
- **Contact Us**: A form for user inquiries and feedback.
- **Admin Panel**: Manage users, products, and orders.

## Technologies Used
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL
- **Payment Gateway**: Razorpay
- **PDF Generation**: pdfkit

## Setup and Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ecommerce-web-app.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd ecommerce-web-app
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Set up the database**:
   - Create a MySQL database.
   - Import the provided `schema.sql` file to create tables.
5. **Configure environment variables**:
   - Add your database credentials and Razorpay API keys in a `.env` file.
6. **Run the application**:
   ```bash
   flask run
   ```
7. **Access the application**:
   - Open `http://localhost:5000` in your browser.

## Database Schema
### Tables
- **usercreate**: Stores user details.
- **admincreate**: Stores administrator details.
- **items**: Contains product information.
- **reviews**: Stores user reviews for products.
- **contact_us**: Records user inquiries.
- **orders**: Tracks order details and status.

## Razorpay Integration
- Payments are processed securely using the Razorpay API.
- Users can select products, proceed to payment, and receive confirmation.

## PDF Invoice Generation
- Upon successful payment, a PDF invoice is generated and available for download.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch.
4. Submit a pull request.

---
Thank you for exploring our e-commerce web application!

