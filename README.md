💸 Income & Expense Tracker
Easily track your spending and income, powered by Flask and MySQL.

🌈 Overview
This web application helps you keep a clear and organized record of all your income and expenses. Categorize each transaction (e.g., Food, Rent, Salary), update your records as life changes, and always know where your money goes.

🚀 Features
Add, update, delete income and expense entries

Assign categories to each record

Simple web interface for fast data entry

MySQL-backed for reliable storage

📦 Installation
Clone the repository

bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
Create a virtual environment (recommended)

bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
Install Python dependencies

bash
pip install -r requirements.txt
Set up MySQL

Install MySQL server if not already installed.

Create a database and update your app.py:

MYSQL_HOST, MYSQL_USER, MYSQL_PASSWORD, MYSQL_DB

(Optional) Import provided SQL schema if included.

Run the application

bash
python app.py
Open your browser to http://localhost:5000.

🧩 Usage
Add entries: Submit your income or expense details and pick a category (e.g., Food, Rent).

Edit or delete: Easily update or remove transactions.

Categorize: See where your money goes by grouping transactions by category.

🛠️ Tech Stack
Python 3.x

Flask

flask_mysqldb

MySQL

HTML/CSS (via Flask templates)

🤝 Contributing
Contributions are welcome! Fork the repo, create a feature branch, and submit a pull request.

📄 License
This project is licensed under the MIT License.

