# Library Management System

This is a simple console-based Library Management System implemented in Python. The system allows users to manage books and members, and supports basic operations such as searching, adding, and deleting books and members, as well as borrowing and returning books.

## Features

- **Admin Login**
  - Access to main menu for book and member management.
  - Add, search, and delete books.
  - Add, search, and delete members.

- **Member Login**
  - Search for books by name or author.
  - Borrow and return books.

## How It Works

### Main Menu

When you start the program, you'll be greeted with a login dashboard:

```
| LOGIN DASHBOARD  |
| 1. Admin Login   |
| 2. Member Login  |
```

Choose between Admin and Member login.

---

### Admin Operations

- **Login Credentials:**  
  - Username: `Faique`
  - Password: `12345`

- **Admin Main Menu:**
  ```
  | Main Menu:        |
  | 1. Book Details   |
  | 2. Member Details |
  | 3. Log Out        |
  ```
- **Book Management:**
  - Add Book: Enter book name and author to add a new book.
  - Search Book: Search for books by name.
  - Delete Book: Delete a book by name.

- **Member Management:**
  - Add Member: Enter member name and CNIC (used as ID).
  - Search Member: Search for a member by CNIC.
  - Delete Member: Delete a member by CNIC.

---

### Member Operations

- **Login:**  
  - Enter your name and CNIC (as password) to log in (must be a registered member).

- **Member Main Menu:**
  ```
  | --- Main Menu ---|
  | 1. Search book   |
  | 2. Borrow book   |
  | 3. Return book   |
  | 4. Log Out       |
  ```

- **Book Search:**  
  - Search by book name or author name.

- **Borrow/Return Book:**  
  - Enter the serial number of the book to borrow or return.

---

## How to Run

1. Open the Jupyter notebook file `Library_management_system.ipynb`.
2. Run all cells to start the program.
3. Follow the on-screen prompts to interact with the system.

## Data Structures

- `books`: A list of dictionaries containing book information.
- `members`: A list of dictionaries containing member information.

## Note

- The system is entirely in-memory (data is not persisted after shutdown).
- Login credentials are hardcoded for demonstration purposes.
- Passwords are input hidden using `getpass` for security.

## Example Usage

```
Welcome to library management system
| LOGIN DASHBOARD  |
| 1. Admin Login   |
| 2. Member Login  |
Enter your choice: 1
---- Admin Login ----
Enter your ID: Faique
Enter your password: 12345
Access granted. Welcome admin!
| Main Menu:        |
| 1. Book Details   |
| 2. Member Details |
| 3. Log Out        |
```

## License

This project is for educational purposes.
