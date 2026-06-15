# 🥛 Neel Dairy - Django E-Commerce Website

Neel Dairy is a full-featured e-commerce web application developed using Django. The platform enables customers to browse dairy products, manage their shopping cart and wishlist, place orders, and complete payments securely through Razorpay integration. The project demonstrates modern web development concepts including authentication, database management, payment gateway integration, and responsive user interaction.

## 🚀 Features

### User Management
- User Registration & Login
- Secure Authentication System
- Password Change & Password Reset
- Customer Profile Management
- Address Management

### Product Management
- Product Listing
- Product Categories
- Product Search Functionality
- Product Details View
- Product Images and Descriptions

### Shopping Features
- Add to Cart
- Update Cart Quantity
- Remove Items from Cart
- Wishlist Management
- Dynamic Cart Calculations

### Order & Payment
- Razorpay Payment Gateway Integration
- Checkout System
- Order Placement
- Order Tracking
- Payment Status Management

### Admin Panel
- Product Management
- Customer Management
- Order Management
- Payment Monitoring
- Wishlist Monitoring

---

## 🛠️ Tech Stack

### Backend
- Python
- Django

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript

### Database
- SQLite

### Payment Gateway
- Razorpay

### Authentication
- Django Authentication System

---

## 📂 Database Models

### Product
Stores product information such as:
- Title
- Selling Price
- Discounted Price
- Description
- Category
- Product Image

### Customer
Stores customer information:
- Name
- Mobile Number
- Address
- City
- State
- Zipcode

### Cart
Maintains products added by users.

### Wishlist
Stores favorite products for users.

### Payment
Tracks Razorpay payment details and payment status.

### OrderPlaced
Stores order details, quantity, payment information, and delivery status.

---

## 📌 Product Categories

- Milk
- Curd
- Lassi
- Milkshake
- Paneer
- Ghee
- Cheese
- Ice Creams

---

## ⚙️ Installation Guide

### Clone Repository

```bash
git clone https://github.com/yourusername/neel-dairy.git
cd neel-dairy
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Admin User

```bash
python manage.py createsuperuser
```

### Run Development Server

```bash
python manage.py runserver
```

Open your browser:

```text
http://127.0.0.1:8000/
```

---

## 🔐 Razorpay Configuration

Add your Razorpay credentials in settings.py:

```python
RAZOR_KEY_ID = "your_key_id"
RAZOR_KEY_SECRET = "your_secret_key"
```

---

## 📸 Key Functionalities

✔ User Authentication

✔ Product Search

✔ Category-wise Product Listing

✔ Shopping Cart

✔ Wishlist

✔ Secure Payment Gateway

✔ Customer Address Management

✔ Order Tracking

✔ Admin Dashboard

---

## 🔮 Future Enhancements

- Product Reviews & Ratings
- Email Notifications
- Discount Coupons
- Inventory Management
- REST API Development
- Analytics Dashboard
- Mobile Application Support

---

## 👨‍💻 Author

**Aditya Karanjekar**

Python Developer | Django Developer | Web Developer

---

## 📄 License

This project is developed for educational and learning purposes.

⭐ If you found this project useful, please give it a star on GitHub.



