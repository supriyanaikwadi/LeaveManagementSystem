#  Leave Management System – Java Console Application

This project is a Java-based Leave Management System for managing employee leave requests, reporting hierarchies, and administrative approvals. It is a console-driven application ideal for academic purposes or small-scale implementations.

---

##  Project Structure

| File Name               | Description |
|------------------------|-------------|
| `Admin.java`           | Admin functionalities such as viewing employee leaves and approving/rejecting them |
| `Employee.java`        | Handles employee leave applications and profile actions |
| `Login.java`           | User authentication and login logic for admin and employees |
| `Leave_Main.java`      | Entry point of the application; manages navigation between modules |
| `Reporting_Authority.java` | Handles approval hierarchy and escalation process |

---

##  Features

-  Role-based login system (Admin and Employee)
-  Apply, approve, or reject leave requests
-  Leave status tracking and reporting authority flow
-  Simple console input/output system for interaction
-  Admin access to all employee leave data

---

##  Technologies Used

- Language: `Java`
- Input/Output: Java Console (Scanner)
- OOP Concepts: Classes, Objects, Inheritance

---

##  How to Run

1. Make sure you have Java installed (JDK 8 or later).
2. Compile all `.java` files:

   ```bash
   javac .java
   ```

3. Run the main class:

   ```bash
   java Leave_Main
   ```

---

##  Roles

- Admin
  - View all leave requests
  - Approve/Reject employee leaves
- Employee
  - Apply for leave
  - Check leave status

---

##  Sample Workflow

1. User logs in via `Login.java`
2. If user is:
   - Admin → redirect to `Admin.java`
   - Employee → redirect to `Employee.java`
3. Leaves are processed and forwarded using `Reporting_Authority.java`
4. Application logic controlled by `Leave_Main.java`

---

