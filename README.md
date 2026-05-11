# Library System Activity

This is a simple PHP-based Library Management System made for academic purposes. The project uses Object-Oriented Programming (OOP) and is organized into different folders for entities, repositories, services, views, and configurations.

The system helps manage books, students, and borrowing records in a more organized way.

---

## Project Structure

```bash
2026-library-system-activity/
│
├── composer.json
├── legacy_library_system.php
├── README.md
├── docs/
│
└── src/
    ├── config/
    ├── Entity/
    ├── Exception/
    ├── public/
    ├── Repository/
    ├── Service/
    └── View/
```

---

## Features

* Manage books and students
* Borrowing records system
* Organized OOP structure
* Custom exception handling
* Composer autoload support
* Simple and easy-to-read project structure

---

## Requirements

Make sure you have the following installed:

* PHP 8.2 or higher
* Composer
* XAMPP, Laragon, or any local server

---

## How to Run the Project

### 1. Open the project folder

```bash
cd 2026-library-system-activity
```

### 2. Install dependencies

```bash
composer install
```

### 3. Start the server

```bash
php -S localhost:8000 -t src/public
```

### 4. Open in browser

```text
http://localhost:8000
```

---

## Main Files and Folders

### Config

Contains the settings for the system.

### Entity

Contains the main classes like:

* Book
* Student
* BorrowRecord

### Repository

Handles storing and retrieving data.

### Service

Contains the main logic of the library system.

### View

Contains the pages shown to the user.

### Exception

Contains custom error handling classes.

---

## Running Tests

Run PHPUnit tests using:

```bash
vendor/bin/phpunit
```

---

## Author

Sean Jairus Adante

Made for school and learning purposes.

---

## License

Open-source project for educational use.
