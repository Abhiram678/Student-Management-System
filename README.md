
# 🎓 Student Management System 

A complete multi-window desktop application built using **Python (Tkinter)** and **SQLite** to manage student registrations, course management, and result records with an intuitive graphical user interface.

---

## 📌 Features

- ✅ **User Authentication**  
  - Registration with validation  
  - Secure login with password check   

- 🎓 **Student Admission Management**  
  - Add, update, delete, and search students  
  - Each student identified by a unique roll number  

- 📘 **Course Management**  
  - Add new courses with description and fees  
  - Edit, delete, and search courses  
  - Course names are unique to prevent duplication  

- 📝 **Result Management**  
  - Enter marks and calculate percentage automatically    

- 📊 **Dashboard**  
  - Display total students, courses, and results  
  - Real-time updates after every operation  

- 🖥️ **Multi-Window GUI**  
  - Clean, modular, and responsive layout  
  - Seamless navigation across windows (Login, Dashboard, Courses, Students, Results)

---

## 🛠️ Tech Stack

| Component         | Technology             |
|------------------|------------------------|
| Language          | Python 3.x             |
| GUI Framework     | Tkinter                |
| Database          | SQLite3 (local storage)|
| Platform          | Desktop (Cross-platform)|

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Abhiram678/student-management-system.git
cd student-management-system
````

### 2. Run the application

```bash
python login.py
```

> Make sure Python 3.x is installed and added to your system path.

---

## 🧾 Folder Structure

```
student-management-system/
│
├── main.py                  # Entry point
├── login.py                 # Login and registration window
├── dashboard.py             # Main dashboard after login
├── course.py                # Course management window
├── student.py               # Student admission window
├── result.py                # Result entry and view
├── database.db              # SQLite database file (auto-generated)
├── assets/                  # Optional images/icons
└── README.md                # Project documentation
```


#
