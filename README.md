# 📚 Library Management System (Spring Boot)

A modern RESTful API for managing library operations, including books, members, and borrowing records. This project is built as part of the **IBM Back-End Development Professional Certificate**, utilizing the latest Java features.

## 🛠️ Tech Stack
* **Java 25 (LTS)** 🚀
* **Spring Boot 3.4+**
* **Maven** (Dependency Management)
* **Spring Web** (REST Endpoints)
* **SLF4J** (Logging)

## 📂 Project Structure
The project follows a clean layered architecture:
* `model`: Data entities (Book, Member, BorrowingRecord) using modern Java types.
* `service`: Business logic and in-memory data management.
* `controller`: REST API endpoints and request handling.

## ⚙️ How it Works
This application currently uses **In-Memory Storage** (ArrayLists).
> **Note:** Data is not persistent and will be reset every time the application restarts.

## 🚀 Getting Started
To run this project locally:
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/library-management-system.git](https://github.com/YOUR_USERNAME/library-management-system.git)
2. Ensure you have JDK installed.

3. Run the application:
    ```bash
    mvn spring-boot:run