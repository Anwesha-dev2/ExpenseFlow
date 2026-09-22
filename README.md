ExpenseFlow

### Expense Reimbursement Management System

ExpenseFlow is a backend project I am building using **Core Java, JDBC and MySQL**.

The main idea is to manage employee expenses and their approval and reimbursement process.

## What it does

- Employees can submit expenses
- Employees can view their expenses
- Managers can approve or reject expenses
- Finance can process reimbursements
- Expense status can be tracked
- Reports can be generated using SQL
- Important actions can be recorded in an audit log

## Technology Used

- Java
- JDBC
- MySQL
- SQL
- MySQL Workbench
- VS Code
- Git & GitHub

## Database

The project currently uses four main tables:

- `users`
- `expenses`
- `approvals`
- `audit_log`

The database files are kept separately:

```text
database/
├── schema.sql
├── sample_data.sql
└── queries.sql
