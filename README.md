# 👔 Employee Management CLI App (Node.js + MongoDB)

A simple command-line interface application for managing employee records, built with **Node.js**, **Mongoose**, and **MongoDB**.

This CLI allows you to insert employee data, view all records, and sort employees by salary (ascending or descending).

## 📦 Features

- ✅ Connects to local MongoDB
- 👤 Add new employee with salary
- 📄 View all employee records
- 📈 Sort employee records by salary (ascending or descending)
- 📟 Interactive terminal menu

## 🛠️ Tech Stack

- Node.js
- MongoDB
- Mongoose (ODM)
- readline (for CLI interaction)

## 📁 Project Structure
employee-cli-app/ <br />
├── index.js # Main CLI logic <br />
├── package.json # Dependencies and scripts <br />

## 🚀 Getting Started

### 1. Clone the Repository

git clone https://github.com/your-username/employee-management-cli.git
cd employee-management-cli

### 2. Install Dependencies

npm install

### 3. Start MongoDB Server

Ensure MongoDB is running on your machine at: mongodb://localhost:27017/Employeedb

### 4. Run the Application
node index.js

### 🧑‍💻 CLI Menu Options

--- Employee Management CLI ---<br />
1. Insert Employee
2. View All Employee
3. Ascending order    
4. Descending order    
5. Exit
-------------------------------
