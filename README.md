# 🚴 Bike Rental Shop - Bash & PostgreSQL Project

This is a project from the [freeCodeCamp Relational Database Certification](https://www.freecodecamp.org/learn/relational-database/).  
It involves using **Bash scripting** and **PostgreSQL** to build a Bike Rental Shop system that manages customer reservations and bike inventory.

---

## 📚 Project Objective

- Learn how to work with PostgreSQL relational databases
- Automate SQL queries using Bash
- Build a working CLI (Command-Line Interface) for a Bike Rental Shop

---

## 🛠️ Technologies Used

- **PostgreSQL**
- **Bash Shell**
- **Gitpod** (or any Unix/Linux terminal)

---

## 🚀 Features

- Create and manage a PostgreSQL database
- Insert and retrieve customer and rental data
- Use `psql` commands within a Bash script
- Prevent duplicate data entries
- Handle conditional logic using Bash

---

## 📁 Files Included

- `bike-shop.sql` – SQL file with table creation and sample data
- `bike-shop.sh` – Bash script that automates SQL commands
- `README.md` – Project documentation

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/bike-rental-shop.git
   cd bike-rental-shop
2. Run the SQL file to create the database:
   psql -U postgres -f bike-shop.sql
3. Run the Bash script:
   ./bike-shop.sh

