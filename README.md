💰 Expense Management System

A full-stack application built with Python and SQL to track, manage, and analyze personal expenses. The project includes a modular backend for database operations and a frontend interface for easy expense management, with built-in analytics for spending insights.

🚀 Features

Add / Update Expenses – Record daily expenses with category, date, and amount

Expense Analytics – Visualize expenses by month and category

Database Integration – SQL backend with modular helpers for clean design

Logging – Centralized logging for debugging and monitoring

APIs – Backend APIs for smooth data flow between database and frontend

Automated Tests – Unit tests for backend functions to ensure reliability

Frontend UI – Simple interface to manage and track expenses easily

🛠️ Tech Stack

Programming Language: Python

Database: SQL (SQLite/MySQL)

Backend: Python with modular DB helpers & APIs

Frontend: Python (PyQt / Tkinter-based UI)

Testing: Pytest

Logging: Python Logging Library

📂 Project Structure
expense-management-system/
│── backend/
│   ├── db_helper.py        # Database operations
│   ├── logging_setup.py    # Logging configuration
│   └── server.py           # Backend server logic
│
│── frontend/
│   ├── app.py              # Main application
│   ├── add_update_ui.py    # Add/Update expense UI
│   └── analytics_ui.py     # Analytics dashboard
│
│── database/
│   └── expense_db_creation.sql   # Database schema
│
│── tests/
│   ├── backend/test_db_helper.py # Unit tests
│   └── conftest.py
│
│── requirements.txt        # Dependencies
│── README.md               # Documentation

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/your-username/expense-management-system.git
cd expense-management-system


Install dependencies

pip install -r requirements.txt


Create the database

sqlite3 expense.db < database/expense_db_creation.sql


(or use MySQL depending on your setup)

Run the application

python frontend/app.py

📊 Screenshots (Optional)

(You can add screenshots of the UI once you run it.)

📈 Future Improvements

Add authentication (multi-user support)

Export reports to Excel/CSV

Cloud database integration

Mobile-friendly version

👨‍💻 Author

Pranjal Sinha
B.Tech – Metallurgical & Materials Engineering, PEC Chandigarh
🔗 LinkedIn
 | GitHub
