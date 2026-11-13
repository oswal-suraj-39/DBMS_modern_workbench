# 🗄️ DBMS Modern Workbench (Web-Based)

## 📌 Project Overview

This project is a web-based Database Management System (DBMS) that allows users to create, manage, and interact with databases and tables through a graphical user interface.

It is designed to simulate features similar to database tools like MySQL Workbench, focusing on usability, dynamic UI, and real-time interaction.

---

## 🚀 Features

* Developed a dynamic table creation interface supporting multiple data types, Primary Key, NOT NULL, UNIQUE, AUTO_INCREMENT, UNSIGNED, and DEFAULT constraints.
* Implemented CRUD operations (Create, Read, Update, Delete) for table records.
* Integrated MySQL INFORMATION_SCHEMA queries to retrieve table metadata, including column information and key constraints.
* Developed a visual SQL SELECT query builder supporting WHERE, GROUP BY, HAVING, ORDER BY, and LIMIT clauses.
* Implemented a custom SQL query editor for executing SQL statements and displaying query results.
* Developed REST API endpoints using Node.js and Express.js for frontend-backend communication.
* Implemented PDF export functionality using PDFKit to generate downloadable table reports.
* Designed an interactive user interface featuring dark/light themes, dynamic search, keyboard shortcuts, and draggable popup windows.
  
---

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript
* AngularJS (SPA architecture)

### Backend

* Node.js
* Express.js

### Database

* MySQL

---

## ⚙️ Project Structure

* `/frontend` → UI files (HTML, CSS, JS)
* `/backend` → Server-side logic (Node.js, Express)
* `/database` → MySQL schema and queries

---

## 🔧 How It Works

1. User interacts with the UI (create DB, tables, etc.)
2. Frontend sends requests using JavaScript (fetch / API calls)
3. Backend (Node.js + Express) processes requests
4. MySQL executes queries
5. Response is sent back and UI updates dynamically

---

## ▶️ Setup Instructions

1. Install required tools:

   * Node.js
   * MySQL
   * Visual Studio Code with the ```live server``` extension

2. Clone the repository:

   ```
   git clone https://github.com/oswal-suraj-39/DBMS_modern_workbench.git
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Configure database:

   * Create MySQL database
   * Update connection details in backend ```server.js```

5. Run the server on Visual Studio Code terminal:

   ```
   cd server; node server.js
   ```

6. Open in Visual Studio Code:
    * Click on ```Go Live``` at the bottom bar in Visual Studio Code

---

## 📸 UI Highlights

* Dynamic table creation forms
* Editable data grid
* SQL query editor
* Popup-based interactions

---

## 🎯 Project Goals

* Learn full-stack development
* Understand DBMS concepts practically
* Build a real-world database interface
* Improve UI/UX and performance

---

## 📌 Future Improvements

* User authentication
* Role-based access control
* Export/import database
* Query history
* Performance optimization

---

## 👨‍💻 Author

**Oswal Suraj**
📧 [oswalsuraj369@gmail.com](mailto:oswalsuraj369@gmail.com)

---

## 📜 License

This project is licensed under the MIT License.
You may use and modify it, but proper credit must be given.

---

## ⭐ Notes

* This project focuses on learning DBMS concepts through implementation
* UI is inspired by modern database tools
* Not intended for production use (yet)
