# 📚 Library Management System

A beginner-friendly **Library Management System built using Python** in Jupyter Notebook. The project helps manage books, library members, and book issue and return operations. It uses JSON files to store records so that data can be retained between program runs.

## ✨ Features

- **Add Books:** Add new books with a unique book ID, title, and number of copies.
- **View Books:** Display the available books in the library.
- **Search Books:** Search for books by title.
- **Member Registration:** Register library members with unique member IDs.
- **Issue Books:** Issue books to registered members after checking availability.
- **Return Books:** Return issued books and update the available copy count.
- **Track Issued Books:** View borrowing records and return status.
- **Data Persistence:** Store books, members, and issue records in JSON files.
- **Menu-Driven Interface:** Perform operations through a simple interactive menu.

## 🛠️ Technologies Used

- **Python 3** — Core programming language
- **Jupyter Notebook** — Development and execution environment
- **JSON** — File-based data storage
- **Built-in Python Libraries:** `json` and `os`

## 📁 Project Structure

```text
Library-Management-System/
│
├── Library_Management_System.ipynb
├── books.json
├── members.json
├── issues.json
└── README.md
```

**Note:** The JSON files are created automatically when the program saves data. They may not exist before the first run.

## 🚀 Getting Started

### Prerequisites

- Python 3 installed
- Jupyter Notebook or JupyterLab installed

### Installation and Execution

1. Clone or download this repository.

   ```bash
   git clone <your-repository-url>
   ```

2. Open the project folder.

   ```bash
   cd Library-Management-System
   ```

3. Start Jupyter Notebook.

   ```bash
   jupyter notebook
   ```

4. Open `Library_Management_System.ipynb`.

5. Run the notebook cells **in order**, starting with the imports and helper functions, followed by the individual operations.

6. Run the final menu cell to start using the application.

## 💻 How to Use

When the program starts, an interactive menu lets you select an operation.

| Option | Operation |
|---|---|
| 1 | Add a book |
| 2 | View all books |
| 3 | Search for a book |
| 4 | Register a member |
| 5 | Issue a book |
| 6 | Return a book |
| 7 | View issued books |
| 8 | Exit the program |

*The option numbers correspond to the menu implementation in the notebook.*

### Example Workflow

1. Add a book with ID `B101`, title `Python Basics`, and 3 copies.
2. Register a member with ID `M101`.
3. Issue the book to that member.
4. Check the available copies — the count decreases from 3 to 2.
5. Return the book.
6. Check the available copies again — the count returns to 3.

## 💾 Data Storage

The project uses three JSON files:

- `books.json` — Stores book details and copy availability.
- `members.json` — Stores registered member information.
- `issues.json` — Stores book issue and return records.

This provides simple file-based storage without requiring an external database server.

**Database note:** JSON is used for persistence in this version; MySQL or SQLite is not currently integrated.

## 🧠 Concepts Demonstrated

This project demonstrates practical Python programming concepts, including:

- Variables and data types
- Lists and dictionaries
- Conditional statements and loops
- Functions and modular programming
- File handling
- JSON serialization and deserialization
- Input validation
- Searching and updating records
- Basic data management

## 🔮 Future Enhancements

The project can be extended with:

- Due dates and overdue tracking
- Borrowing limits per member
- Fine calculation for late returns
- Book categories and author-based search
- SQLite or MySQL database integration
- A graphical user interface using Tkinter or Flask
- Reports and visual analytics
- Automated testing and improved error handling

## 🎯 Learning Outcome

This project provides hands-on experience in developing a menu-driven Python application, managing related records, validating user input, and maintaining data between sessions.

It is suitable as a **beginner-level Python project** and can be enhanced further to demonstrate database management, application design, and more advanced programming concepts.

## 👩‍💻 Author

**Shreya Soni**

B.Tech — Information Technology

---

*Built with Python and Jupyter Notebook for learning and practice.*
