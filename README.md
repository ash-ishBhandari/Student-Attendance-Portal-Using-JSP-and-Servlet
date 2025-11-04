# Student Attendance Portal Using JSP and Servlet

## 🎯 Objective
Develop a student attendance portal using JSP as frontend and Servlet + JDBC as backend.

## 📂 Project Structure
```
StudentAttendancePortal/
├── src/com/example/servlet/AttendanceServlet.java
├── WebContent/attendance.jsp
├── WebContent/success.jsp
└── WebContent/WEB-INF/web.xml
```

## ⚙️ Setup Instructions
1. Create MySQL database `schooldb`.
2. Run the following SQL:
   ```sql
   CREATE TABLE Attendance (
       ID INT AUTO_INCREMENT PRIMARY KEY,
       StudentID VARCHAR(20),
       Date DATE,
       Status VARCHAR(10)
   );
   ```
3. Update MySQL credentials in `AttendanceServlet.java`.
4. Deploy on Apache Tomcat.
5. Access the portal:
   ```
   http://localhost:8080/StudentAttendancePortal/attendance.jsp
   ```

## 🧠 Demonstrated Concepts
- JSP for user interface
- Servlet for backend logic
- JDBC for database operations
- MVC (Model-View-Controller) pattern
