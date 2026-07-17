
# 🎓 Student Attendance Management System

## 📖 Project Overview

The Student Attendance Management System is a web-based application developed to simplify the process of recording and managing student attendance. It eliminates manual attendance registers by allowing administrators or faculty members to mark attendance digitally. The system securely stores attendance records in a database, making it easy to retrieve, update, and monitor attendance information.

This project is built using Java Servlets, JSP, JDBC, MySQL, HTML, CSS, and Apache Tomcat.

# 🚀 Features

- 👨‍🎓 Student Registration
- 🔐 Admin Login
- 📝 Mark Student Attendance
- 📅 Date-wise Attendance Management
- 🔍 Search Student by Roll Number
- 📊 View Attendance Records
- ✏️ Update Attendance
- ❌ Delete Attendance Records
- 💾 Store Attendance in MySQL Database
- 🎨 Responsive User Interface

# 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JSP

### Backend
- Java
- Java Servlets
- JDBC

### Database
- MySQL

### Server
- Apache Tomcat

### IDE
- Eclipse IDE
- 
# 📂 Project Structure

StudentAttendanceManagement/
│
├── src/
│   ├── com.attendance/
│   │      ├── LoginServlet.java
│   │      ├── StudentServlet.java
│   │      ├── AttendanceServlet.java
│   │      └── DBConnection.java
│
├── WebContent/
│   ├── index.jsp
│   ├── login.jsp
│   ├── dashboard.jsp
│   ├── attendance.jsp
│   ├── student.jsp
│   ├── css/
│   └── images/
│
├── database/
│      attendance.sql
│
└── README.md

# ⚙️ Project Flow

## Step 1: Start the Application

The user opens the application through the browser.

↓

## Step 2: Login

The administrator enters username and password.

↓

## Step 3: Dashboard

After successful login, the dashboard provides options such as:

- Add Student
- Mark Attendance
- View Attendance
- Update Attendance
- Delete Attendance

↓

## Step 4: Student Registration

The administrator enters:

- Student Name
- Roll Number
- Course
- Branch
- Year

The information is stored in the MySQL database.

↓

## Step 5: Mark Attendance

The administrator enters the student's Roll Number.

The system verifies the student.

If found:

- Present
- Absent

Attendance is saved with the current date.

↓

## Step 6: Database Storage

Attendance data is stored in the Attendance table.

↓

## Step 7: View Attendance

The administrator can view attendance records for all students.

↓

## Step 8: Update Attendance

Existing attendance records can be modified.

↓

## Step 9: Delete Attendance

Incorrect attendance records can be deleted.

↓

## Step 10: Logout

The administrator logs out securely.

# 🗄️ Database Tables

## Student Table

| Column |
|---------|
| ID |
| Name |
| Roll Number |
| Course |
| Branch |
| Year |


## Attendance Table

| Column |
|---------|
| Attendance ID |
| Student ID |
| Roll Number |
| Attendance Date |
| Status (Present/Absent) |

# 📊 System Workflow

Start
   │
   ▼
Login
   │
   ▼
Dashboard
   │
   ├───────────────┐
   ▼               ▼
Add Student   Mark Attendance
   │               │
   ▼               ▼
Save Student   Enter Roll Number
                   │
                   ▼
            Student Exists?
              │         │
             Yes        No
              │         │
              ▼         ▼
      Mark Present/Absent
              │
              ▼
     Save Attendance
              │
              ▼
      View Attendance
              │
              ▼
   Update/Delete Records
              │
              ▼
           Logout
              │
              ▼
             End


# 🎯 Objectives

- Reduce manual paperwork.
- Improve attendance accuracy.
- Maintain secure attendance records.
- Provide quick access to attendance history.
- Simplify attendance management.

# 💡 Future Enhancements

- QR Code Attendance
- Face Recognition Attendance
- RFID Attendance
- Email Notifications
- SMS Alerts
- Student Login
- Faculty Login
- Attendance Reports (PDF/Excel)
- Cloud Database Integration
- Mobile Application Support

# 📸 Screenshots

Add screenshots of:

- Home Page
- <img width="767" height="676" alt="image" src="https://github.com/user-attachments/assets/0483320d-80e5-4ae9-922d-6a2292d8506f" />

- Login Page
- <img width="533" height="560" alt="image" src="https://github.com/user-attachments/assets/5caf2b52-14a8-43ce-83b7-7670e1f375af" />

- Dashboard
- <img width="1532" height="565" alt="image" src="https://github.com/user-attachments/assets/0e053ad0-0058-44ec-b3ad-86e39197f56c" />

- Student Registration
- <img width="1536" height="588" alt="image" src="https://github.com/user-attachments/assets/1086df72-6496-4fc5-b1a6-b331a0580321" />
-<img width="750" height="370" alt="image" src="https://github.com/user-attachments/assets/c6c3b682-2258-43a1-baba-709fef6b4671" />
-Teacher Registration
-<img width="1536" height="627" alt="image" src="https://github.com/user-attachments/assets/f822d04f-8bec-4b62-bfdf-1a9a1c74a793" />
-<img width="759" height="372" alt="image" src="https://github.com/user-attachments/assets/c5cb2e89-8247-41c0-9a8c-38985651c265" />

- Attendance Page
- <img width="1920" height="1080" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/f8678f1f-f87e-4e3b-88dd-c9786c1cf311" />
- Attendance Records

<img width="1920" height="1080" alt="Screenshot (65)" src="https://github.com/user-attachments/assets/b2257bb8-5441-4e44-8f42-5f5a8b8da12d" -/>
# 👩‍💻 Author

**Varshini Reddy**

Student Attendance Management System


# 📄 License

This project is developed for educational and learning purposes.


# ⭐ If you found this project helpful, don't forget to Star ⭐ this repository.
