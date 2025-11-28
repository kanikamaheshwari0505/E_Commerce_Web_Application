🛒 E-Commerce Web Application (Django)

->A fully functional E-Commerce Web Application built using Django.
Users can browse products, add them to their cart, and place orders, while admins manage products, users, and orders through a dedicated dashboard.

🚀 Features
👤 User Features

*User Signup / Login / Logout

*Browse products by category

*Search and filter products

*View detailed product pages

*Add to cart / update quantity / remove items

*Checkout with order summary

*View past order history

🛠️ Admin Features

*Add / Edit / Delete products

*Manage categories

*Manage orders & order status

*Manage users

*Django Admin Panel

🏗️ Tech Stack

*Backend: Django

*Frontend: HTML, CSS, Bootstrap

*Database: SQLite3

*Tools: Django ORM, Django Templates, Session-based cart

📂 Project Structure
E_Commerce_Web_Application/
│── accounts/          # User authentication app
│── shop/              # Products, categories, cart, orders
│── templates/         # HTML templates
│── static/            # CSS, JS, Images
│── db.sqlite3         # Database
│── manage.py          # Django management file
│── requirements.txt   # Dependencies

⚙️ How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/kanikamaheshwari0505/E_Commerce_Web_Application.git
cd E_Commerce_Web_Application

2️⃣ Create virtual environment
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run migrations
python manage.py migrate

5️⃣ Run the server
python manage.py runserver


Open the browser on:
👉 http://127.0.0.1:8000/

⭐ Why This Project is Unique

*Clean and modular Django structure

*Realistic features similar to real e-commerce websites

*Fully functional cart + checkout system

*Beginner-friendly and easy to extend

*Admin dashboard for complete backend management

📌 Future Enhancements

*Payment gateway (Razorpay / Stripe)

*Wishlist feature

*Product reviews & ratings

*User profile dashboard

*Email notifications for orders

❤️ Made with Django
