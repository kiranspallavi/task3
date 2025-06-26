# 📊 SQL Developer Internship – Task 3

### ✅ Task Title: Writing Basic SELECT Queries

This task focuses on retrieving data from a structured database using `SELECT`, `WHERE`, `LIKE`, `ORDER BY`, `LIMIT`, and other foundational SQL clauses.

---

## 🧩 **Domain**: Online Bookstore

This task builds on the existing database from Task 1 and Task 2, which simulates an online bookstore with tables like:

- `Users`
- `Authors`
- `Books`
- `Orders`
- `OrderItems`
- `Payments`
- `Categories`

---

## 🎯 **Objectives**

- Retrieve data using `SELECT`
- Apply filters using `WHERE`, `LIKE`, `IN`, and `BETWEEN`
- Sort results using `ORDER BY`
- Limit results using `LIMIT`
- Use `DISTINCT` and column aliasing (`AS`)

---

## 📁 **Files Included**

- `task3_queries.sql` – SQL file with all 20 SELECT queries.
- `README.md` – This documentation file.

---

## 📜 **Sample Queries**

| # | Description | Query Example |
|--:|-------------|---------------|
| 1 | All books with prices | `SELECT title, price FROM Books;` |
| 2 | Books between ₹200 and ₹500 | `SELECT * FROM Books WHERE price BETWEEN 200 AND 500;` |
| 3 | Users with NULL email | `SELECT * FROM Users WHERE email IS NULL;` |
| 4 | Top 3 expensive books | `SELECT * FROM Books ORDER BY price DESC LIMIT 3;` |
| 5 | Books containing "Harry" | `SELECT title FROM Books WHERE title LIKE '%Harry%';` |

---

## 🧠 **Concepts Demonstrated**

- `SELECT *` vs specific columns
- `WHERE` filtering with:
  - `AND`, `OR`, `IN`, `BETWEEN`, `IS NULL`, `LIKE`
- `ORDER BY` with `ASC` and `DESC`
- `LIMIT` for top results
- `DISTINCT` to get unique values
- `AS` for aliasing column names

---

## 🛠 Tools Used

- **DB Browser for SQLite** / **MySQL Workbench**
- MySQL or SQLite engine

---

## ▶️ How to Run

1. Load your existing **OnlineBookstore** schema from Task 1.
2. Ensure data is populated as per Task 2.
3. Run the script `task3_queries.sql` line by line.
4. Observe the output for each query.

---

## 📸 Screenshots (Optional)

Include screenshots of:
- DB result windows
- Output of top 5 queries
- Filtered/Sorted data examples

> You can add a `/screenshots` folder and embed them here using markdown syntax:
> `![Query Output](screenshots/query1.png)`

---

## 📤 Submission

- Push this task folder to a **new GitHub repository** named:  
  `sql-internship-task-3`
- Submit your GitHub link here:  
  [Submission Form](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

## 🧾 Interview Questions Covered

- What does `SELECT *` do?
- How do you filter rows?
- What is `LIKE '%value%'`?
- What is `BETWEEN` used for?
- How do you limit output rows?
- Difference between `=` and `IN`
- Sorting with `ORDER BY`
- Aliasing using `AS`
- What is `DISTINCT`?
- What is the default sort order?

---

## 🧑‍💻 Author

**Name**: _Your Name Here_  
**Date**: _DD-MM-2025_  
**Track**: SQL Developer Internship

---
