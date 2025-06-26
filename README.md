# 📚 Library Management System (Java Console Application)

## ✅ Objective
A simple **Library Management System** built using **Java** and **Object-Oriented Programming (OOP)** concepts. This console-based application allows users to manage books and perform operations such as issuing and returning books.

---

## 🛠️ Tools & Technologies
- Java (JDK 8 or above)
- VS Code / IntelliJ IDEA
- Terminal / Command Prompt

---

## 🧱 Project Structure
The system is organized into multiple classes:

### 1. `Book.java`
- Represents a book with properties like `id`, `title`, `author`, and `isIssued`.
- Methods to issue and return the book.

### 2. `User.java`
- Represents a library user.
- Stores issued books.
- Methods to issue and return books from the user's side.

### 3. `Library.java`
- Manages a collection of books and users.
- Handles core functionalities:
  - Add books/users
  - Issue and return books
  - Display available books

### 4. `Main.java`
- Provides a menu-driven interface for interaction.
- Uses `Scanner` to get user input.
- Demonstrates the full working of the library system.

---

## 🔍 Features
- Add books and users to the system.
- Issue a book to a user (if available).
- Return a book from a user.
- Display all books along with their status (Available/Issued).
- Menu-based command-line interface.

---

## 🚀 Getting Started

### 1. Clone or Download the Repository

```bash
git clone https://github.com/your-username/library-management-system-java.git
cd library-management-system-java
2. Compile and Run
Using Command Line:
bash
Copy
Edit
javac *.java
java Main
Using VS Code / IntelliJ:
Open the project folder.

Run Main.java.

🧪 Sample Data
Already included:

📘 Books: "The Alchemist", "Java Basics"

👤 Users: Yusuf (ID: 101), Ayesha (ID: 102)

📝 Future Enhancements
Add file storage for book/user data persistence.

Limit the number of books a user can borrow.

Implement due dates and fine calculation.

Add user authentication and roles (admin/user).

👨‍💻 Author
Yusuf Saiyad
Java Developer | Passionate about OOP and backend systems.
