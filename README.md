# Python Tic-Tac-Toe with SQL Persistence

An object-oriented desktop application that not only runs the classic game but persists player history and session scores into a relational database.

## 🚀 Key Features
* **Persistent Data:** Uses a MySQL backend to store match history and player scores across sessions.
* **OOP Architecture:** Modular design separating UI (`main_page.py`), Auth (`login_page.py`), and Database (`connection.py`) logic.
* **Analytics:** Real-time score updates utilizing transactional SQL queries.

## 🛠️ Technologies
* **Language:** Python 3.11+
* **GUI:** Tkinter
* **Database:** MySQL
* **Libraries:** `mysql-connector-python`, `tabulate`

## ⚙️ Setup & Installation
1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/yourusername/tic-tac-toe-sql.git](https://github.com/yourusername/tic-tac-toe-sql.git)
    ```
2.  **Database Setup:**
    * Import `tic_tac_toe.sql` into your MySQL workbench to create the `score` and `player` tables.
3.  **Configuration:**
    * Update `constants.py` with your local database credentials.
4.  **Run:**
    ```bash
    python login_page.py
    ```
