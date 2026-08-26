# 🛋️ Modern Furniture Store

A web-based **Modern Furniture Store** developed using PHP, MySQL, HTML, CSS, JavaScript, and Composer. The application provides an online furniture shopping experience with product browsing, cart management, checkout, user accounts, and an administration panel.

## 📌 Features

### 👤 User Features

* User registration and login
* User profile management
* Browse furniture products
* View detailed product information
* Add products to cart
* Update and remove cart items
* Checkout and order processing
* View orders and order details
* Contact form

### 🔐 Admin Features

* Admin login
* Manage products
* Add new products
* Edit existing products
* Delete products
* Manage users
* Manage customer orders
* View contact/customer reports

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3, SCSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Dependency Management:** Composer
* **Development Environment:** XAMPP
* **Version Control:** Git & GitHub

## 📂 Project Structure

```text
SEM-6 PROJECT/
│
├── img/                    # Product and website images
├── vendor/                 # Composer dependencies (not included in Git)
│
├── composer.json           # Composer configuration
├── composer.lock           # Composer dependency lock file
├── .gitignore              # Git ignored files
│
├── login.php               # User login
├── register.php            # User registration
├── logout.php              # Logout
├── profile.php             # User profile
│
├── product.php             # Product listing
├── details.php             # Product details
├── add_product.php         # Add product
├── edit_product.php        # Edit product
├── delete_product.php      # Delete product
├── manage_products.php     # Product management
│
├── cart.php                # Shopping cart
├── checkout.php            # Checkout
├── orders.php              # Orders
├── order_process.php       # Order processing
│
├── admin.php               # Admin panel
├── manage_users.php        # User management
│
└── contact.php             # Contact page
```

## ⚙️ Installation & Setup

### 1. Install XAMPP

Install XAMPP and start:

* Apache
* MySQL

### 2. Clone the Repository

```bash
git clone https://github.com/anshu0609/furn-modern-furniture-store.git
```

Move the project into:

```text
C:\xampp\htdocs\
```

### 3. Install Composer Dependencies

Open the project directory in a terminal:

```bash
composer install
```

This will automatically create the `vendor` folder.

### 4. Configure the Database

Create a MySQL database using **phpMyAdmin** and configure the database connection according to your local environment.

> Update the database credentials in the project's database configuration file before running the application.

### 5. Run the Project

Start Apache and MySQL from XAMPP and open:

```text
http://localhost/SEM-6%20PROJECT/
```

## 🔒 Security

Sensitive configuration files such as `.env` are excluded from the Git repository using `.gitignore`.

The Composer `vendor` directory is also excluded because dependencies can be recreated using:

```bash
composer install
```

## 🎓 Project Information

**Project:** Modern Furniture Store
**Type:** Web Application
**Technology:** PHP & MySQL
**Environment:** XAMPP
**Version Control:** GitHub

## 👨‍💻 Author

**Anshu Jha**

GitHub:
https://github.com/anshu0609
