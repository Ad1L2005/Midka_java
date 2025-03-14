# Employee Management System

Employee Management System is a Java-based application using Hibernate and Gradle for managing employee data and related processes.

## 📂 Project Structure
```
employee_management_system/
├── build.gradle
└── src/
    └── main/
        ├── java/
        │   └── org/
        │       └── example/
        │           ├── Main.java               // Entry point
        │           ├── HibernateUtil.java      // Hibernate configuration
        │           └── entity/                 // Entities
        │               ├── Employee.java       // Employee entity
        │               ├── Attendance.java     // Attendance tracking
        │               ├── LeaveRequest.java   // Leave requests
        │               ├── Payroll.java        // Payroll management
        │               ├── PerformanceReview.java // Performance reviews
        │               ├── Position.java       // Job positions
        │               └── WorkTime.java       // Work hours tracking
        └── resources/                          // Configuration files (e.g., hibernate.cfg.xml)
```

## 📋 Features
- Manage employee records (Create, Read, Update, Delete)
- Track attendance and work hours
- Handle leave requests
- Manage payroll information
- Conduct performance reviews
- Store job position details

## 📌 Technologies Used
- Java 17+
- Hibernate ORM
- Gradle (build automation tool)
- H2 Database (embedded database)

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd employee_management_system
   ```

2. **Build the project:**
   ```bash
   ./gradlew build
   ```

3. **Run the application:**
   ```bash
   ./gradlew run
   ```

## 🛠 Configuration
- Ensure `hibernate.cfg.xml` is correctly configured with database details.

## 📖 Example Output
```
Employee Management System Initialized
Employee{id=1, name='John Doe', position='Software Engineer'}
```

## 📜 License
This project is licensed under the MIT License.

