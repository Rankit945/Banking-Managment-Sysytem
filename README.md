# Banking Management System (Clear GUVI‑Friendly Documentation)

A simple and easy **Banking Management System** built in Java with MySQL.
This guide is written in very simple language so anyone can understand quickly.

---

## 📂 Folder Structure

```
/ (root)
├─ Code/               → All Java files
├─ Icons/              → Images used in UI
├─ Jcalendar/          → Calendar library
├─ SQL/                → SQL dump file
├─ Bank Management System.iml
└─ README.md
```

---

## ✅ What You Need

* Java JDK (8 or above)
* IntelliJ IDEA
* MySQL Server
* MySQL Workbench

---

## 🚀 How to Setup (Very Easy)

### **1. Download the Project**

Just download or clone the project from GitHub.

---

### **2. Import Database in MySQL Workbench**

1. Open **MySQL Workbench**
2. Click **Server → Data Import**
3. Choose **Import from Self-Contained File**
4. Select the SQL file from the **SQL** folder
5. Choose schema name: `bankSystem`
6. Click **Start Import**

Database setup is done.

---

### **3. Open Project in IntelliJ IDEA**

1. Open IntelliJ
2. Click **Open** → choose the project folder
3. Set JDK (File → Project Structure)
4. Add MySQL connector JAR if required

---

### **4. Run the App**

1. Open **Code** folder
2. Open **Login.java**
3. Right‑click → **Run**

The Login / Signup window will open.

---

## 🔐 Login Instructions

* If you already have an account → enter **Account Number** + **PIN**
* If you are new → click **Signup** → fill your details → get system‑generated PIN

---

## ❗ Common Issues

**Database connection error?**

* Check MySQL is running
* Check username/password in code

```
jdbc:mysql://localhost:3306/bankSystem
user: root
password: your_password
```

**SQL import not working?**

* Make sure you selected the correct SQL file

---

## 🎉 Done!

Your banking management system is ready to use.

---

## 📘 GUVI Guidelines Compliance

This repository follows GUVI project guidelines by providing:

### ✔ Clear Folder Structure

All folders (Code, SQL, Icons, Jcalendar) are properly organized and easy to understand.

### ✔ Complete README (This File)

This README clearly explains:

* Project overview
* Prerequisites
* Installation steps
* Database import instructions
* How to run the project
* Common errors & fixes

### ✔ Simple Setup Instructions

Anyone can set it up by following step‑by‑step guidance.

### ✔ Java + MySQL Integration Explained

Database connectivity requirements and configurations are included.

If GUVI asks for more sections like **Screenshots**, **Demo Video Link**, or **Project Features**, tell me—I'll add them instantly!

If you want an even more simple version or want screenshots, tell me! 😊
