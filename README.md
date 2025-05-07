# car-rental-system
This is a web-based Car Rental System that allows users to browse, book, and rent cars online. It includes modules for user registration, car listings, booking management, and admin control. The system helps both customers and administrators manage rentals efficiently.

---

## 🛠️ Requirements

- PHP 7.x or later
- MySQL Server (e.g., XAMPP, WAMP, or MAMP)
- Web browser (Chrome, Firefox, etc.)

---

## 🚀 How to Run the Project

1. **Clone or Download the Project**
   ```bash
   git clone [https://github.com/your-username/car-rental-project.git](https://github.com/mathan1232/car-rental-system.git)

Or simply download the ZIP and extract it.

Move the Project to Web Directory

If using XAMPP: Move the folder to C:\xampp\htdocs\car-rental-project

Start Apache and MySQL

Open XAMPP/WAMP/MAMP and start Apache and MySQL.

Import the Database

Open phpMyAdmin in your browser: http://localhost/phpmyadmin

Create a new database (carrental)

Configure Database Connection

Open the database config file (e.g., includes/config.php)

Update it with your local MySQL username, password, and database name:
$db = new PDO("mysql:host=localhost;dbname=car_rental_db", "root", "");
Libraries Used
FPDF – for generating downloadable invoices in PDF format.

PHPMailer – for sending emails (like booking confirmation, password reset, etc.).
