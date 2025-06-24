<<<<<<< HEAD
# Ecommernce-Website
=======

# 🛒 BlinkIt-Clone-Full-Stack-Ecommerce

An advanced full-stack e-commerce platform inspired by Blinkit, built using the **Full stack** (MongoDB, Express.js, React.js, Node.js). This project features real-world functionalities like:

- 🔐 Secure user authentication with access & refresh tokens
- ✉️ OTP-based email verification
- 🔁 Password recovery and reset
- 📦 Product uploads (Admin panel)
- 🗂️ Category and Subcategory management
- 🛍️ Shopping cart, wishlist, and order placement
- 👩‍💻 Admin dashboard for managing users, products & orders

---

## ⚙️ Tech Stack

- **Frontend:** React.js, Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (access & refresh tokens), OTP via email
- **File Uploads:** Multer & Cloudinary
- **Email Service:** NodeMailer

---

## 🚀 Features

### 🧑 User Features
- Register & Login
- OTP-based email verification
- Access & refresh token authentication
- Forgot/reset password
- Browse products by category/subcategory
- Add to cart, wishlist
- Place orders & view order history

### 🛠️ Admin Features
- Admin authentication
- Product create/edit/delete
- Upload images using Cloudinary
- Category & Subcategory management
- User management
- View and manage orders

---

## 🔐 Authentication Flow

- Uses **JWT access token** (short-lived) & **refresh token** (stored in HTTP-only cookie)
- OTP sent to email during registration for verification
- Password recovery via email link

## ScreenShot

![Alt text](Thumnails.png?raw=true "Title")


## Video
![Alt text](Demo%201.gif?raw=true "demo1")
![Alt text](Demo%202.gif?raw=true "demo2")


## 🧪 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/blinkit-clone.git
cd blinkit-clone

cd client
npm install
cd ../server
npm install

## Set up environment variables

### Create .env in the /server folder with:
 
PORT=5000
MONGO_URI=your_mongo_db_uri
JWT_SECRET=your_jwt_secret
JWT_REFRESH_SECRET=your_refresh_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

## Run the application

# In /server
npm run dev

# In /client
npm run dev
>>>>>>> c986047 (Initial commit)
