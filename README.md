# SQL-Problem-Solving

# SQL Daily Practice 

This repository contains my daily SQL problem-solving practice.

I solve SQL problems regularly to improve:

* Query writing skills
* Problem-solving ability
* Database concepts
* Interview preparation
* Analytical thinking

---

# Topics Covered 

* SELECT Statements
* WHERE Clause
* ORDER BY
* GROUP BY
* HAVING
* Aggregate Functions
* JOINS
* SELF JOIN
* Subqueries
* CASE WHEN
* Conditional Aggregation
* Date Functions
* NULL Handling
* Window Functions *(coming soon)*
* CTE *(coming soon)*

---

# Platforms Used 

* LeetCode
* HackerRank
* SQLBolt
* Interview Query

---

# Folder Structure 

```bash
SQL-Daily-Practice/
│
├── Easy/
├── Medium/
├── Hard/
└── README.md
```

---

# Problems Solved 

| Day | Problem Name                               | Difficulty | Concepts                 |
| --- | ------------------------------------------ | ---------- | ------------------------ |
| 1   | Duplicate Emails                           | Easy       | GROUP BY, HAVING         |
| 2   | Customers Who Never Order                  | Easy       | LEFT JOIN, NULL          |
| 3   | Employees Earning More Than Their Managers | Easy       | SELF JOIN                |
| 4   | Department Highest Salary                  | Medium     | GROUP BY, MAX, Subquery  |
| 5   | Average Selling Price                      | Medium     | JOIN, BETWEEN, AVG       |
| 6   | Queries Quality and Percentage             | Medium     | CASE WHEN, Aggregation   |
| 7   | Monthly Transactions I                     | Medium     | GROUP BY, SUM, CASE WHEN |

> More problems will be added daily.

---

# Goals 

* Solve SQL problems daily
* Strengthen database fundamentals
* Prepare for coding interviews
* Improve query optimization skills
* Learn advanced SQL concepts

---

# What I Learned 

Through these problems I learned:

* How GROUP BY works internally
* Difference between WHERE and HAVING
* Importance of JOINs
* Real-world reporting queries
* Conditional aggregation using CASE WHEN
* How analytics dashboards are built using SQL

---

# Sample SQL Query 

```sql
SELECT departmentId,
       MAX(salary)
FROM Employee
GROUP BY departmentId;
```

---
# Keep Learning 

"Practice SQL daily and database thinking becomes natural."
