# Task 7 – SQL Views

## 🎯 Objective
To create and use SQL Views to simplify data access, enhance abstraction, and demonstrate usage of `WITH CHECK OPTION`.

---

## 🗂 Tables

### Departments
- DeptID (INT, PK)
- DeptName (VARCHAR)

### Employees
- EmpID (INT, PK)
- EmpName (VARCHAR)
- Salary (INT)
- DeptID (FK → Departments.DeptID)

---

## 🧪 Views Created

1. **AllEmployees** – Displays all employee data  
2. **HighPaidEmployees** – Filters employees with salary > 50000  
3. **EmployeeDepartmentView** – Joins Employees and Departments  
4. **HRView** – Only employees from HR (DeptID = 1), with `WITH CHECK OPTION` to restrict insertions

---

## 🛠 Tools Used
- MySQL Workbench / DB Browser for SQLite


