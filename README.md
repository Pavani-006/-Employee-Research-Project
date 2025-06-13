## Employee Research Project

This is a basic database schema project named **Employee Research Project**. It includes two primary tables: `Employee` and `FundingAgency`. This schema can serve as a foundation for managing data related to employees and the agencies funding their research.

## 🗃️ Database Schema

### 1. `Employee` Table

Stores information about employees, including their unique Social Security Number (SSN), name, and salary.

```sql
CREATE TABLE Employee (
    SSN INT PRIMARY KEY,
    Emp_Name VARCHAR(50),
    Salary DECIMAL
);
```

- **SSN**: Social Security Number (Primary Key)
- **Emp_Name**: Name of the employee
- **Salary**: Salary of the employee

 2. `FundingAgency` Table

Stores details about funding agencies, such as their ID, name, and address.

```sql
CREATE TABLE FundingAgency (
    Agency_ID INT PRIMARY KEY,
    Name VARCHAR(100),
    Address VARCHAR(255)
);
```

- **Agency_ID**: Unique identifier for the funding agency (Primary Key)
- **Name**: Name of the funding agency
- **Address**: Address of the funding agency

 💡 Purpose

This project provides a simple relational structure for:
- Tracking employee data relevant to research initiatives.
- Managing associated funding agency information.

 📂 Usage

You can use this schema in SQL-based environments such as:
- MySQL
- PostgreSQL
- SQL Server
- SQLite (with minor datatype adjustments)




