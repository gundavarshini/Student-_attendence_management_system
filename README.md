
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
- Login Page
- Dashboard
- Student Registration
- Attendance Page
- Attendance Records

# 👩‍💻 Author

**Varshini Reddy**

Student Attendance Management System


# 📄 License

This project is developed for educational and learning purposes.


# ⭐ If you found this project helpful, don't forget to Star ⭐ this repository.
