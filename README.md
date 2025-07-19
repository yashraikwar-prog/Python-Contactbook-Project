# 📒 Python ContactBook 1

A simple and user-friendly **Contact Book** built using Python. This console-based application allows users to manage contacts by adding, viewing, updating, searching, and deleting entries. It's a great beginner-level project to understand file handling, functions, and basic data structures in Python.

## 📌 Features

* Add new contacts (name, phone number, email, address)
* View all saved contacts
* Search contacts by name or phone number
* Update existing contact information
* Delete contacts
* Data stored persistently using text or JSON files

## 🛠️ Tech Stack

* **Language**: Python 3
* **Interface**: Command-Line Interface (CLI)
* **Data Storage**: Text file (`.txt`) or JSON (`.json`)

## 📂 Project Structure

```
contact_book/
├── main.py              # Main application logic
├── contact.py           # Contact class definition
├── contact_manager.py   # Functions to handle contact operations
├── data/                # (Optional) Directory for storing contact data
├── README.md            # Project documentation
```

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/contact-book-python.git
   cd contact-book-python
   ```

2. Run the main program:

   ```bash
   python main.py
   ```
   
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 📇 Python with SQL Db Contactbook 2 
A robust **Contact Book** application built using **Python** and **SQL** (SQLite/MySQL/PostgreSQL). This project allows users to perform CRUD (Create, Read, Update, Delete) operations on contacts stored in a relational database. It’s ideal for learning database integration with Python and practicing SQL queries in real-world scenarios.

## 📌 Features

* Add new contacts (name, phone, email, address)
* View all saved contacts
* Search contacts by name or phone number
* Update contact details
* Delete contacts
* Uses SQL database for data storage and management

## 🛠️ Tech Stack

* **Language**: Python 3
* **Database**: SQLite / MySQL / PostgreSQL
* **Libraries**: `sqlite3`, `mysql-connector-python`, or `psycopg2`
* **Interface**: Command-Line Interface (CLI)

## 📂 Project Structure

```
contact_book_sql/
├── main.py              # Main app logic with menu and user interaction
├── db.py                # Handles database connection and setup
├── contact_manager.py   # All CRUD functions using SQL queries
├── schema.sql           # SQL script to create the contacts table
├── README.md            # Project documentation
```

## 🗃️ Database Schema (SQLite Example)

```sql
CREATE TABLE contacts (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT NOT NULL,
    phone TEXT NOT NULL UNIQUE,
    email TEXT,
    address TEXT
);
```

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/contact-book-sql.git
   cd contact-book-sql
   ```

2. Set up the database:

   * If using SQLite: The database file will be created automatically.
   * If using MySQL/PostgreSQL: Create the database and run `schema.sql`.

3. Run the application:

   ```bash
   python main.py
   ```
   
