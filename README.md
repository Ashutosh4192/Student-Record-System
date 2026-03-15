# 🎓 Student Report Card Management System

A simple **C++ console-based application** that manages student report
cards using **file handling**. This project allows users to create,
view, modify, and delete student academic records.

It is built using **C++**, **file streams**, and basic **data
structures** to demonstrate fundamental programming concepts.

------------------------------------------------------------------------

## 📌 Features

-   ➕ Create a student report card
-   📄 View all student report cards
-   🔍 View a specific student's report card using roll number
-   ✏️ Modify an existing student record
-   📊 View student result (marks, sum, and average)
-   ❌ Delete a student record
-   💾 Persistent storage using **binary file handling**

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   **C++**
-   **File Handling (fstream)**
-   **Structures**
-   **Windows Console API**
-   **Binary File Storage**

------------------------------------------------------------------------

## 📂 Project Structure

Student-Report-Card-System/ │ ├── main.cpp \# Main source code ├──
Report.txt \# Binary file storing student records (auto generated) └──
README.md \# Project documentation

------------------------------------------------------------------------

## 📊 Student Data Structure

Each student record contains:

  Field                         Type
  ----------------------------- ------------
  Name                          char\[80\]
  ID                            char\[80\]
  Roll Number                   int
  Programming Marks             float
  Computer Architecture Marks   float
  Writing Skills Marks          float
  Algebra Marks                 float
  Total Sum                     float
  Average                       float

------------------------------------------------------------------------

## ⚙️ How It Works

The system stores student data in a **binary file (`Report.txt`)**. Each
operation reads or writes records from this file.

### Main Menu

1.  Create Student Report Card
2.  View All Student Report Cards
3.  View Single Student Report Card
4.  Modify Report Card
5.  View Result
6.  Delete Record

Users interact through a **console-based interface**.

------------------------------------------------------------------------

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

git clone
https://github.com/your-username/student-report-card-system.git

### 2️⃣ Compile the Program

Using g++

g++ main.cpp -o report

### 3️⃣ Run the Program

Linux / Mac: ./report

Windows: report.exe

------------------------------------------------------------------------

## 💡 Concepts Demonstrated

This project demonstrates several important **C++ programming
concepts**:

-   Structures
-   File Handling
-   Binary File Storage
-   Menu Driven Programs
-   Console UI
-   Data Persistence
-   CRUD Operations

------------------------------------------------------------------------

## ⚠️ Limitations

-   Designed for **Windows only** because it uses `windows.h`
-   No authentication or security
-   Console-based interface
-   No database integration

------------------------------------------------------------------------

## 🚀 Possible Future Improvements

-   Add **database support (MySQL / PostgreSQL)**
-   Build a **GUI version**
-   Add **user authentication**
-   Generate **PDF report cards**
-   Add **grade calculation system**

------------------------------------------------------------------------

## 📜 License

This project is for **educational purposes** and can be freely used and
modified.

------------------------------------------------------------------------

⭐ If you found this project useful, consider **starring the
repository**.
