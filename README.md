Personal Expense Tracker (Java + Python + SQL)

📌 Project Overview
The Personal Expense Tracker is a command-line application that helps users efficiently track their daily expenses. The project integrates Java for backend logic, SQL (MySQL) for database management, and Python for data visualization. Users can add expenses, view expenses, check total expenses, and analyze their spending patterns using graphical representations.

🛠️ Tech Stack
Java – Backend processing and CLI interface

MySQL – Database for storing expenses

Python (Pandas, Matplotlib) – Data visualization for expense analysis

🚀 Features
✅ Add Expenses – Users can input expenses with a category and amount.
✅ View Expenses – Displays all recorded expenses with categories and amounts.
✅ Total Expenses – Shows the total sum of all expenses.
✅ Data Visualization – Generates a pie chart for expense distribution by category.

📊 Data Flow
1️⃣ User inputs expense details → Java processes and stores the data in MySQL
2️⃣ User views or totals expenses → Java retrieves and displays the data
3️⃣ Python fetches stored data → Generates graphs for analysis

🔧 How to Run the Project
1️⃣ Setup MySQL Database
Create a database: create database expense_db;
Use the database: use expense_db;
Create a table:
CREATE TABLE expenses (
    id INT AUTO_INCREMENT PRIMARY KEY,
    category VARCHAR(255),
    amount DECIMAL(10,2)
);
2️⃣ Run Java Code 
I have used eclipse to run the java code that is ExpenseTracker.java
3️⃣ Run Python Visualization
I have used visual studio code to execute python code that is ExpenseAnalysis.ipynb

Thank you so much :) Hope everyone likes my work.
