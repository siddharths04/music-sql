# Music Store SQL Queries

This repository contains a file **Music_store_queries.sql**, which holds various SQL queries I used to answer specific questions about a hypothetical music store database. Being a newbie to SQL, I initially didn’t know the questions, so I utilized ChatGPT to guide me in forming these queries. Below is the project description and the structure of the queries.

## SQL Queries for Music Store Database

The queries are categorized by complexity, starting from basic to advanced, and answer a variety of business questions using key SQL concepts such as joins, subqueries, Common Table Expressions (CTEs), and recursive queries.

## 📝 Features:
- **Basic Queries**: Retrieve information such as the senior-most employee, countries with the most invoices, and top invoice totals.
- **Moderate Queries**: Identify the best customers, list all Rock music listeners, and find the top artists by track count.
- **Advanced Queries**: Analyze customer spending on artists, determine the most popular genre by country, and find the top customer by total spending per country.

## 📚 Key SQL Concepts Covered:
- Multi-table `JOIN` operations (e.g., `customer`, `invoice`, `artist`, `track`, etc.)
- Aggregations with `GROUP BY` and `ORDER BY`
- Use of Common Table Expressions (CTEs) and Recursive Queries
- Window functions such as `ROW_NUMBER()` for advanced data ranking
- Subqueries for complex filtering and calculations

## 📂 Structure:
- **Q1 - Q5 (Basic)**: Introductory queries focused on simple business analysis.
- **Q6 - Q8 (Moderate)**: More in-depth queries analyzing Rock music listeners, artists, and song lengths.
- **Q9 - Q11 (Advanced)**: Complex queries involving customer spending per artist, popular genres by country, and identifying top customers by country.

## 🔑 Usage:
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/music-store-sql-queries.git
    ```
2. Import the provided dataset to your SQL environment.
3. Run the queries in your SQL editor to explore the insights from the music store data.

## 📊 Example Queries:
- **Best Customer**: Who has spent the most money in the store?
- **Top Rock Artists**: Which artists have written the most Rock tracks?
- **City with Highest Revenue**: Where should we throw a promotional event based on total revenue?

## 🧠 Learning Outcomes:
By exploring this repository, you will:
- Gain hands-on experience with SQL queries of varying complexity.
- Understand how to join multiple tables, perform aggregations, and use CTEs.
- Learn how to apply SQL to answer real-world business questions using relational databases.

---

Feel free to explore the SQL code, modify the queries, and test them on your own dataset. Contributions are welcome!
