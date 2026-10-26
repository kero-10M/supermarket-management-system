# Supermarket Sales & Inventory Management System

## Overview
A relational database application built with Microsoft Access to manage day-to-day supermarket operations. Co-developed as a team project, this system covers inventory tracking, supplier relations, customer data and sales processing through forms, queries and reports.

## Key Features
* **Relational Architecture:** 7 related tables (Products, Customers, Suppliers, Categories, Units, Sales_Header, Sales_Details) linked by relationships to keep the data consistent.
* **Inventory Management:** Update queries (`Add_Stock`, `Deduct Stock`) that add stock from supplier deliveries and deduct it after sales.
* **Pricing:** Update queries that apply a percentage discount or a price increase to a product by name (`Discount _% By Name`, `Increase_% By Name`, `Update_Dairy_Prices`).
* **Queries and Reporting:** Select queries and reports for profit, low-stock alerts, daily sales, customer payments, product search and invoice printing.
* **Data Cleanup:** Delete queries for old records and empty invoices (`Delete By Date`, `Delete Empty Invoice`).
* **Forms:** Forms for customers, products, suppliers, a main page and a report selection screen.

## Tech Stack
* **Database & GUI:** Microsoft Access
* **Language:** SQL (queries and data manipulation)

## Database Contents
| Object | Count | Examples |
|---|---|---|
| Tables | 7 | Products, Customers, Suppliers, Categories, Units, Sales_Header, Sales_Details |
| Queries | 14 | 7 select (Profit, Low Stock, Invoice_Print...), 5 update (Add_Stock, Deduct Stock...), 2 delete |
| Forms | 6 | Main_Page, Navigation Form, Products, Customers, Suppliers, report's_selection |
| Reports | 10 | Profit, Low Stock, Invoice_Print, Customer_Payments... |

## My Contribution and Team
**Kerollus Adel:** designed the tables and the relationships between them, and wrote the queries.
**A teammate:** built the forms and the reports.

## System Showcase

### 1. Entity-Relationship Diagram (ERD)
The relationships between the sales, inventory and entity tables.
![Relationships](Screenshot%202026-10-26%20215000.png)

### 2. Checkout Dashboard
Sales processing and customer management screen.
![Checkout](Screenshot%202026-10-26%20215100.png)

### 3. Main Navigation Hub
Central screen for reaching the rest of the system.
![Main Page](Screenshot%202026-10-26%20215113.png)

### 4. Navigation Form
Secondary navigation screen.
![Navigation Form](Screenshot%202026-10-26%20215244.png)

### 5. Products Management
Screen for updating prices and stock quantities.
![Products Details](Screenshot%202026-10-26%20215255.png)

### 6. Reports Selection
Screen for choosing a report.
![Reports Selection](Screenshot%202026-10-26%20215304.png)

### 7. Suppliers Management
Screen for managing supplier details and contact information.
![Suppliers Details](Screenshot%202026-10-26%20215313.png)

## Author
Kerollus Adel (database design and queries), with a teammate (forms and reports).
