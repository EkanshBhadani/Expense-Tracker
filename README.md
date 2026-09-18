# 💰 Personal Expense Tracker

A Python, MySQL, Pandas and Matplotlib based Personal Expense Tracker developed as a CBSE Class 12 Informatics Practices project.

The application allows users to store and manage expenses across multiple months, search records using multiple conditions, analyse monthly spending patterns, and visualize financial data through graphs.

---

## 📌 Overview

The Personal Expense Tracker is designed to provide a simple way to record and analyse personal expenses.

The project uses:

- **MySQL** for permanent data storage
- **Python** for application logic
- **Pandas** for data retrieval, filtering and analysis
- **Matplotlib** for data visualization
- **Jupyter Notebook** as the development and execution environment

The system maintains expense records in a MySQL database and uses Pandas DataFrames whenever data needs to be searched, analysed or visualized.

---

## ✨ Features

### 📝 Expense Management

The system supports complete CRUD operations:

- **Create** — Add a new expense
- **Read** — Search and view existing expenses
- **Update** — Modify an existing expense using its `EXP_ID`
- **Delete** — Remove an expense using its `EXP_ID`

Each expense contains:

| Field | Description |
|---|---|
| `EXP_ID` | Unique expense identifier |
| `EXP_DATE` | Date of the expense |
| `EXP_NAME` | Name of the expense |
| `CATEGORY` | Expense category |
| `AMOUNT` | Amount spent |
| `PAY_METHOD` | Payment method used |

---

## 🔎 Dynamic Search

The search system works on the **complete database**, independently of the month selected for analysis.

Users can search by:

1. Expense ID
2. Date range
3. Expense name
4. Category
5. Amount
6. Payment method

### Multiple Search Conditions

Multiple conditions can be combined dynamically.

## ⚙️ Prerequisites

Before running this project, the following software and Python libraries must be installed and configured on the system.

### Required Software

| Software | Purpose | Official Download |
|---|---|---|
| Python | Runs the application | [Python](https://www.python.org/downloads/) |
| MySQL Community Server | Stores the expense database | [MySQL Community Server](https://dev.mysql.com/downloads/mysql/) |
| Jupyter Notebook | Runs the project notebook | [Jupyter](https://jupyter.org/install) |

### Required Python Libraries

The following Python packages are required:

| Library | Purpose |
|---|---|
| `pandas` | Data handling, filtering and analysis |
| `matplotlib` | Data visualization |
| `mysql-connector-python` | Connecting Python to MySQL |
