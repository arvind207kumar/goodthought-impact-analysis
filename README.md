# 📊 Impact Analysis of GoodThought NGO Initiatives

> 🚀 **This is a hands-on SQL project focused on analyzing real-world NGO data using PostgreSQL.**

I built this project to explore how data can reveal the real-world impact of NGO efforts. Using SQL, I analyzed operations from **GoodThought**, a non-profit focused on education, healthcare, and sustainable development across underserved communities.

---

## 🌍 Project Background

The dataset spans from **2010 to 2023**, capturing detailed records of:

- **Assignments**: Each project’s name, timeline, region, budget, and impact score  
- **Donations**: How funds were distributed across assignments and donor types  
- **Donors**: Profiles of individuals and organizations supporting the cause

Here's the ERD diagram that maps out the relationships between these tables:  
`![ERD Diagram](erd.png)`

---

## 🔍 What I Did

I wrote SQL queries to answer two key questions:

1. **Top Donation Assignments**  
   - Find the top five assignments based on total donation value  
   - Categorized by donor type  
   - Output includes assignment name, region, donation amount, and donor type

2. **Top Regional Impact Assignments**  
   - Identify the highest impact score assignment per region  
   - Only includes assignments with at least one donation  
   - Output includes assignment name, region, impact score, and total donations

---

## 🛠️ Tech Stack

| Tool / Language     | Purpose                                 |
|---------------------|------------------------------------------|
| **SQL (PostgreSQL)**| Data querying and transformation         |
| **Jupyter Notebook**| Interactive SQL execution and analysis   |


---

## 📚 Lessons Learned

This project helped me strengthen several core SQL concepts:

- ✅ **Sorting Results**: Used `ORDER BY` to rank assignments by donation value and impact score  
- ✅ **Common Table Expressions (CTEs)**: Simplified complex queries using `WITH` clauses  
- ✅ **Joining Data**: Connected multiple tables using `INNER JOIN` and `LEFT JOIN`  
- ✅ **Grouping & Aggregation**: Applied `GROUP BY` with `SUM()` and `MAX()` to summarize data  
- ✅ **Partitioning**: Leveraged `ROW_NUMBER()` with `PARTITION BY` to isolate top performers per region

---

## 💡 Why It Matters

This project goes beyond technical querying—it's about using data to understand how resources are being used and where they’re making the most difference. It’s a small but meaningful step toward smarter decision-making in the non-profit space.

---

Feel free to explore the SQL notebook and see how data can drive real-world change.
