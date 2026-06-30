# 👥 User Registration & Management System (CRUD)

A lightweight, core PHP web application that provides complete **CRUD (Create, Read, Update, Delete)** operations for managing user profiles. It interfaces directly with a MySQL database using the procedural `mysqli` extension to handle secure record management, data entry, and updates.

---

## 🚀 Features

* **User Registration (Create):** A fully functional form with basic validation to capture user names, email addresses, and passwords[cite: 21].
* **User Directory (Read):** A tabular rendering page that fetches all existing profiles from the database and showcases accounts in an structured format[cite: 24].
* **Profile Management (Update):** An inline update form pre-populated with individual account records dynamically requested via unique GET request ID parameters[cite: 20, 23].
* **Record Purging (Delete):** Safe direct removal of users from the server environment mapping precise parameters using transactional routing[cite: 19].

---

## 🛠️ Technology Stack

* **Backend Logic Engine:** Core PHP (Procedural Syntax)[cite: 18, 19, 20, 22, 23, 24]
* **Database Management:** MySQL (via `mysqli` API drivers)[cite: 18]
* **User Interface:** Clean Semantic HTML5 combined with modular internal CSS component styles[cite: 20, 21, 24]

---

## 📁 Repository Structure & File Mapping

```text
├── db.php       # Database connection initializer executing procedural protocols[cite: 18]
├── index.html   # Main graphical user interface layout presenting the registration form[cite: 21]
├── insert.php   # Execution target accepting user data entries to inject database records[cite: 22]
├── view.php     # System view generator fetching records to structure the main users data table[cite: 24]
├── edit.php     # Dynamic single-record query page rendering updating interfaces based on target account ID[cite: 20]
├── update.php   # Backend processing module executing final MySQL UPDATE queries[cite: 23]
└── delete.php   # Backend execution script containing SQL delete directives targeted by ID parameters[cite: 19]
