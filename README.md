# Inventory Management System — Frontend

A modern and responsive web-based **Inventory Management System (IMS)** designed to manage inventory operations, stock movements, warehouse activities, reporting, and audit tracking through a centralized platform.

The frontend provides role-based interfaces for managing items, stock transactions, transfers, receipts, reports, and other inventory operations.

## 🚀 Features
### 🔐 Authentication & Access Control
* User authentication
* JWT-based authentication
* Role-based access control
* Role-specific navigation and functionality

### 📦 Item Master Data Management
* Item management
* Item Group management
* Item search and filtering
* Item information management

### 📥 Stock Receiving & Initial Stock
* **GRN (Goods Received Note)** management
* Record goods received into inventory
* **Opening Stock** management
* Maintain initial stock quantities

### 🔄 Stock Management
* **Stock Adjustment** for correcting inventory quantities
* **Stock Transfer** between locations/bins
* **Stock Transfer Receipt** for receiving transferred stock
* **Stock Issue** for issuing inventory
* Track stock movements and transaction history

### 📊 Reports & Analytics
* Inventory reports
* Stock movement reports
* Transaction-related reports
* Dashboard analytics
* Search, filtering, and pagination

### 🔍 Audit
* Audit trail for inventory activities
* Track important system operations
* Maintain transaction history for accountability

### 📋 Bin Card
* View item-wise stock movement
* Track stock receipts and issues
* Monitor inventory balance
* Search bin card information by item

## 🛠️ Tech Stack
* **Next.js**
* **React**
* **TypeScript**
* **Tailwind CSS**
* **REST APIs**
* **JWT Authentication**

## 🏗️ Main System Modules
Authentication
     │
     ├── Item Master
     ├── Opening Stock
     ├── GRN
     ├── Stock Adjustment
     ├── Stock Transfer
     ├── Stock Transfer Receipt
     ├── Stock Issue
     │

     ├── Bin Card
     ├── Reports and Audit
     
## 🔗 Backend Integration
The frontend communicates with the Spring Boot backend through RESTful APIs.

The API integration covers:

* Authentication
* Item Master
* GRN
* Opening Stock
* Stock Adjustment
* Stock Transfer
* Stock Transfer Receipt
* Stock Issue
* Bin Card
* Reports
* Audit
* Dashboard analytics

## 👨‍💻 Development Team
Developed by **Bugwarts** as a university Software Project at the **University of Moratuwa — Faculty of Information Technology**.

**Inventory Management System — Bugwarts**
