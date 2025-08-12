# Employee Data Comparison Tool

## 📌 Overview
The **Employee Data Comparison Tool** is a Python-based desktop application that allows users to compare employee records from two CSV files — a **master file** and a **changes file** — to detect:  
- Data modifications  
- Newly added employees  
- Any differences based on a primary key  

The tool provides an **easy-to-use Tkinter GUI** for viewing data, exporting reports as PDFs, and sending them directly via email using Gmail SMTP.  

---

## 🚀 Features
- **CSV Data Loading** – Import master and changes datasets.  
- **Automated Data Comparison** – Detects changes in records using a unique primary key (`SAIL_PERNO`).  
- **New Employee Detection** – Identifies records present in the changes file but not in the master file.  
- **GUI Display** – Clean table view using Tkinter’s Treeview with scroll support.  
- **PDF Export** – Save changes and new employee lists as professional PDF reports.  
- **Email Integration** – Send reports directly via Gmail SMTP with attachments.  

---

## 🛠 Technologies Used
- **pandas** – Data handling & comparison  
- **tkinter** / **ttk** – GUI design  
- **smtplib** & **email.message** – Email sending functionality  
- **reportlab** – PDF generation  

---
