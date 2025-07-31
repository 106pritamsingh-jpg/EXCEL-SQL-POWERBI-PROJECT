# 📚 Crossword Bookstore Analytics – Excel → SQL → Power BI

## 📌 Project Overview

This project presents an end-to-end analytics pipeline that begins with raw **Excel data**, transforms and analyzes it using **SQL**, and culminates in a fully interactive **Power BI dashboard**. The goal is to derive actionable insights from book sales, customer behavior, and inventory trends over time.

---

## 🧾 Step 1: Data Understanding & Excel Cleanup

The initial dataset included three key tables:
- `Books`: Book-level information including title, author, genre, price, stock, and publish year.
- `Customers`: Customer details such as location (city, country), name, and ID.
- `Orders`: Transactional data including order date, quantity, total amount, and foreign keys.

Tasks in Excel included:
- Removing inconsistencies (like blank cells or malformed values)
- Ensuring referential integrity between books, customers, and orders
- Saving each table as a CSV for import into a database

---

## 🗃️ Step 2: SQL Data Analysis (MySQL)

Once data was cleaned, it was imported into a **MySQL database** (`project_sql`) for structured querying and deeper insights.

Key SQL tasks performed:
- Filtering by genre, year, and country
- Calculating metrics like:
  - Total revenue
  - Total stock
  - Average order value
- Identifying:
  - Top genres by sales
  - Most expensive books
  - Customers with highest spend
  - Remaining stock per book and genre
- Using JOINs and aggregations to bring together transactional and product data
- Applying grouping, sorting, and `HAVING` clauses for segmentation

Advanced queries included:
- Books sold per author and genre
- Monthly order patterns
- Frequently ordered books
- Revenue generated per customer

---

## 📊 Step 3: Data Visualization with Power BI

With the query results and table relationships clearly defined, the final stage was to create a **Power BI dashboard** to visually explore and present insights.

Key dashboard features:
- Total Revenue, Average Order Value, and Customer KPIs
- Line chart showing revenue trends over months
- Genre-wise revenue comparison using bar charts
- Pie chart showing stock distribution by genre
- Top 5 customers by revenue
- Interactive map displaying global customer distribution
- Filters for year and genre to enable dynamic exploration

The visuals are not only informative but also designed to support business decision-making on inventory, sales strategy, and customer engagement.

---

## 🧠 Skills Demonstrated

- **Excel**: Data cleaning, structure validation
- **SQL**: Joins, aggregations, subqueries, data transformations
- **Power BI**: Dashboard design, interactive filtering, visual storytelling
- **Data Analysis**: Generating KPIs, interpreting trends, identifying outliers
- **Database Design**: Linking normalized tables for analysis

---

## 📈 Conclusion

This project showcases how raw data can be transformed into powerful insights using structured SQL logic and intuitive visual storytelling. It reflects real-world analytics scenarios where a combination of tools is used to understand customer behavior, manage inventory, and monitor business performance.


