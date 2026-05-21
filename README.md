# ExpenseFlow

## Expense Reimbursement Management System

ExpenseFlow is a simple Java and MySQL project made to understand how expense reimbursement systems work in companies.

In this project, employees can submit expenses, managers can approve or reject them, and finance can process reimbursements. The project also includes reports and basic validation rules.

---

# Features

- Employee expense submission
- Manager approval/rejection
- Finance reimbursement process
- Expense status tracking
- Monthly expense reports

---

# Technologies Used

- Core Java
- JDBC
- MySQL
- SQL

---

# Database Tables

- users
- expenses
- approvals
- audit_log

---

# Business Rules

- Food expense limit: ₹500
- Travel expense limit: ₹5000
- Only approved expenses can be reimbursed

---

# Workflow

```text
Employee → Manager → Finance
```

```text
SUBMITTED → APPROVED → REIMBURSED
```

OR

```text
SUBMITTED → REJECTED
```

---

# How to Run

1. Run `schema.sql` and `sample_data.sql` in MySQL Workbench
2. Add MySQL JDBC connector inside `lib/`
3. Compile Java files
4. Run `ExpenseApp.java`

---

# Learning From This Project

- JDBC connectivity
- SQL joins and queries
- Role-based workflow
- Backend validation logic
- Database relationships
- Report generation using SQL
- Database design
- Enterprise application concepts
