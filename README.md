# 📦 Inventory and Supply Chain Management System (MongoDB)

## 📖 Project Overview
This project demonstrates an Inventory and Supply Chain Management system using MongoDB.  
It is implemented based on lab experiments focusing on schema validation and data integrity using JSON Schema.

---

## 🎯 Objectives
- To create and manage collections in MongoDB  
- To enforce schema validation rules  
- To ensure data consistency using constraints  
- To simulate a real-world inventory system  

---

## 🧰 Technologies Used
- MongoDB  
- MongoDB Compass  
- MongoDB Shell (mongosh)  

---

## 🧩 Features
- ✅ Collection creation and deletion  
- ✅ Schema validation using JSON Schema  
- ✅ Required fields and data types enforcement  
- ✅ Enum constraints for categories  
- ✅ Range validation for numeric values  
- ✅ Modify validation rules on existing collections  

---

## 🗂️ Collections Used

### 👤 Users
Stores system users such as Admin and Manager.

### 📦 Products
Stores inventory items with validation:
- Product Name  
- Category (Electronics, Clothing, Books, Home Appliances)  
- Price  
- Stock Quantity  
- SKU  

### 🏢 Employees
Stores supply chain staff details:
- Employee ID  
- Name  
- Department  
- Salary  

---

## ▶️ How to Run the Project

1. Open MongoDB Compass  
2. Connect to local server  
3. Open MongoDB Shell  
4. Run the queries step-by-step  
5. Verify using:
   - `db.products.find()`
   - `db.users.find()`
   - `db.employees.find()`
   - `db.getCollectionInfos()`

---


## 🧠 Key Concepts Learned
- NoSQL database structure  
- JSON Schema validation  
- Data integrity in MongoDB  
- Difference between strict and moderate validation  

---

## 🎤 Viva Summary
This project implements an inventory and supply chain system using MongoDB with schema validation including required fields, enum constraints, and range validation.

---

## 👨‍💻 Author
**SANJAYPRASAD M.Y**

---

## 📌 Conclusion
The project successfully demonstrates how MongoDB can be used to manage inventory systems with strong validation rules, ensuring reliable and structured data storage.
