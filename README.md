# 📦 Inventory Management System

A desktop-based **Inventory Management System** developed using **Python**, **Tkinter**, and **MySQL**. The application helps businesses efficiently manage inventory, update stock, search products, generate bills, and maintain transaction records through an easy-to-use graphical interface.

---

## 📖 Project Overview

The Inventory Management System is designed to simplify inventory management for retail shops and small businesses. Instead of maintaining stock records manually, this application stores product information in a MySQL database and provides a desktop GUI built with Tkinter.

The system enables users to:

- Add new products
- Search products using Product ID
- Update stock quantity
- Generate customer bills
- Store transaction history
- Manage inventory efficiently

---

## ✨ Features

- 📦 Add New Products
- 🔍 Search Products by Product ID
- 📊 Update Product Stock
- 💰 Billing System
- 🧾 Generate Bills
- 💾 Store Product Information in MySQL
- 📑 Save Sales Transactions
- 🖥️ Simple and User-Friendly GUI

---

## 🛠️ Built With

- **Python**
- **Tkinter**
- **MySQL**
- **XAMPP**
- **mysql-connector-python**

---

## 📂 Project Structure

```
Inventory-Management/
│
├── main.py
├── add_to_db.py
├── update.py
├── inventory_system.sql
├── README.md
```

---

## ⚙️ Requirements

- Python 3.x
- XAMPP
- MySQL
- VS Code or PyCharm

---

## 📥 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/Rashmirekhamahalik/Inventory-Management-System.git
```

Or download the ZIP file.

---

### Step 2: Install Required Package

```bash
pip install mysql-connector-python
```

---

### Step 3: Start XAMPP

Open **XAMPP Control Panel** and start:

- Apache
- MySQL

---

### Step 4: Create Database

Open your browser:

```
http://localhost/phpmyadmin
```

Create a new database:

```
inventory_system
```

---

### Step 5: Import Database

Click **Import**

Choose

```
inventory_system.sql
```

Click **Go**

This will automatically create the required tables and insert sample data.

---

### Step 6: Run the Application

To add products:

```bash
python add_to_db.py
```

To start the billing system:

```bash
python main.py
```

---

## 🗄️ Database Schema

### Inventory Table

| Column | Description |
|---------|-------------|
| id | Product ID |
| name | Product Name |
| stock | Available Stock |
| price | Product Price |

---

### Transaction Table

| Column | Description |
|---------|-------------|
| id | Transaction ID |
| product_name | Product Name |
| quantity | Quantity Sold |
| amount | Total Amount |
| date | Transaction Date |

---

## 🔄 Workflow

```
Start
   │
   ▼
Open Billing System
   │
   ▼
Enter Product ID
   │
   ▼
Search Product
   │
   ▼
Display Product Information
   │
   ▼
Enter Quantity
   │
   ▼
Generate Bill
   │
   ▼
Update Stock
   │
   ▼
Save Transaction
   │
   ▼
Exit
```

---

## 📸 Screenshots

Add screenshots here:

<img width="1920" height="1080" alt="Screenshot 2026-07-26 133949" src="https://github.com/user-attachments/assets/5d035e36-89b1-4077-a8e6-c87b0328bbbf" />


<img width="1920" height="1080" alt="Screenshot 2026-07-26 134218" src="https://github.com/user-attachments/assets/994f29d4-8c59-4c56-aa9b-47341e109d86" />


<img width="997" height="624" alt="Screenshot 2026-07-26 134531" src="https://github.com/user-attachments/assets/3d655ecd-0bc4-4442-bc57-f450d9a54dff" />

```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Python Programming
- Tkinter GUI Development
- MySQL Database Integration
- CRUD Operations
- SQL Queries
- Event-Driven Programming
- Desktop Application Development

---

## 🚀 Future Enhancements

- User Authentication
- Barcode Scanner Support
- Invoice PDF Generation
- Export Data to Excel
- Product Categories
- Customer Management
- Supplier Management
- Dashboard with Charts
- Sales Reports
- Low Stock Alerts

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 👩‍💻 Author

**Rashmirekha Mahalik**

Python Full Stack Developer

### Skills

- Python
- Django
- MySQL
- Tkinter
- Machine Learning
- Data Analysis
- SQL

---

## ⭐ Show Your Support

If you like this project, please ⭐ star this repository.

---

## 📜 License

This project is developed for educational and learning purposes.

You are free to use, modify, and improve it for personal or academic use.

---

**Thank you for visiting this project!**
