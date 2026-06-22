# ⚙️ Module 6: Advanced SQL for Data Engineering (Views, Procedures, Transactions, & Joins)

Welcome to the sixth module of my SQL learning journey! This specialized module focuses on high-performance database programming and engineering concepts, including database object abstraction, procedural automation, transaction isolation, and advanced relational table merging.

## 📝 Module Overview
In this module, I shifted focus toward advanced database engineering practices designed to optimize execution speed, secure data assets, and streamline query layers. I practiced abstracting complex underlying queries by constructing dynamic virtual tables, known as **Views**, to simplify client access.

To automate server-side database tasks, I learned how to encapsulate operational logic directly inside the database management system using **Stored Procedures**. I evaluated the technical trade-offs of using compiled procedural code, noting their benefits in network performance and disadvantages in migration flexibility. Furthermore, I studied the critical framework of **ACID transactions**, writing robust rollback strategies to ensure complete data integrity during multi-statement operations. Finally, I mastered advanced data modeling by comparing, contrasting, and executing complex explicit **JOIN** operations using phpMyAdmin.

---

## 🧪 Hands-On Labs
This module features four advanced data engineering labs. Click on any lab document to review the exercises and syntax:

* 📄 **[`01_Hands-on Lab: Using Views in MySQL using phpMyAdmin.pdf`](01_Hands-on%20Lab:%20Using%20Views%20in%20MySQL%20using%20phpMyAdmin.pdf)**
    * *Creating virtual tables to secure confidential columns and simplify routine multi-table reporting layout constraints.*
* 📄 **[`02_Hands-on Lab: Stored Procedures.pdf`](02_Hands-on%20Lab:%20Stored%20Procedures.pdf)**
    * *Writing, compiling, and invoking parameterized SQL functions directly inside the database layer.*
* 📄 **[`03_Hands-on Lab: Committing and Rolling Back a Transaction.pdf`](03_Hands-on%20Lab:%20Committing%20and%20Rolling%20Back%20a%20Transaction.pdf)**
    * *Implementing ACID-compliant workflows using `COMMIT` and `ROLLBACK` to handle unexpected data errors gracefully.*
* 📄 **[`04_Hands-on Lab: Working with Joins in MySQL using phpMyAdmin.pdf`](04_Hands-on%20Lab:%20Working%20with%20Joins%20in%20MySQL%20using%20phpMyAdmin.pdf)**
    * *Mastering relational sets by implementing `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, and `FULL OUTER JOIN` operations.*

---

## 🎯 Learning Objectives Completed

* 🖼️ **View Abstraction & Security:** Defined database views and built customized virtual query structures to encapsulate complicated backend data lookups for downstream analytical layers.
* 🤖 **Procedural Automation:** Structured, tested, and executed operational **Stored Procedures** with dynamic inputs to centralize server-side relational computation.
* 🧠 **Architectural Trade-Off Analysis:** Systematically compared the performance advantages of utilizing compiled routines against the hardware constraints and maintenance overheads of database-bound logic.
* 🛡️ **ACID Transaction Compliance:** Described the core significance of database Atomicity, Consistency, Isolation, and Durability (**ACID** parameters) and implemented manual transaction statements to secure multi-step pipeline updates.
* 🧩 **Advanced Relational Joins:** Evaluated and implemented various explicit relational matching styles (`INNER`, `OUTER`, `LEFT`, `RIGHT`) to optimally bind data objects across separate structural entities.

---

## 🛠️ Tech Stack & Tools Used
![MySQL](https://img.shields.io/badge/mysql-%2300758F.svg?style=for-the-badge&logo=mysql&logoColor=white)
![phpMyAdmin](https://img.shields.io/badge/phpmyadmin-6C78AF?style=for-the-badge&logo=phpmyadmin&logoColor=white)
![Data Engineering](https://img.shields.io/badge/Database-Data_Engineering-orange?style=for-the-badge&logo=databricks&logoColor=white)
