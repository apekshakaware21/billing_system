# 🧾 Billing System using Python & Excel (Admin Panel)

A Python-based Billing System with an Admin Panel that manages **Customer Records** and **Billing Information** using **Excel files** for data storage. This lightweight system allows adding, viewing, searching customers, and generating bills with automatic CGST & SGST calculation.

---

## 🚀 Project Overview

This project is a simple **Billing System Admin Panel** built using **Python** and **OpenPyXL** for Excel file handling. It mimics a basic record-keeping and billing workflow suitable for small businesses where data is maintained in spreadsheets.

### Features:
- Add Customer Records (ID, Company Name, Phone No, Email ID)
- View All Customer Records
- Search Customer by ID
- Generate Bills with CGST & SGST calculation
- Data stored and managed in Excel files (`.xlsx`)

---

## ⏳ Duration Taken
| Task                         | Time Spent |
|------------------------------|------------|
| Project Setup & Structure     | 1 Hour     |
| Feature Development           | 3 Hours    |
| Testing & Bug Fixing          | 1 Hour     |
| Documentation & Cleanup       | 1 Hour     |
| **Total Time**                | **6 Hours**|

---

## 🛠 Challenges Faced
- Ensuring data integrity while appending records to Excel sheets.

- Handling input validation (numeric amounts, unique customer IDs).

- Managing Excel read-write locks in a loop-based admin panel.

- Structuring a scalable flow for adding future features like `Update` or `Delete` records.

---

## 📝 Outcome
- Fully functional **Admin Panel** CLI for managing customer records.
- Billing Generation with tax (CGST & SGST) calculations.
- Persistent data storage through Excel files.
- User-friendly, menu-driven interface.
- Ideal for small businesses or learning projects with Excel as backend.

---

## ⚙️ How to Run

### Prerequisites:
- Python 3.x installed
- `openpyxl` library installed
```bash
pip install openpyxl
```

---

## 🎯 Conclusion
This project is a simple yet effective admin panel for billing management using Excel as the database layer. It’s ideal for small business use-cases or as a learning project for file handling in Python. The modular design allows for future scalability (like GUI integration, advanced reporting, or database migration).
