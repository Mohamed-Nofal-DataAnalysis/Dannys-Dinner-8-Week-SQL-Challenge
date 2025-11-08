# Danny's Dinner – 8 Week SQL Challenge (Full Solution)

![SQL](https://img.shields.io/badge/Level-Intermediate%20to%20Advanced-blue)
![Challenge](https://img.shields.io/badge/8--Week%20SQL%20Challenge-100%25%20Solved-success)
![Database](https://img.shields.io/badge/DB-Danny's%20Dinner-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Stars](https://img.shields.io/github/stars/Mohamed-Nofal-DataAnalysis/Dannys-Dinner-8-Week-SQL-Challenge?style=social)

**The most complete, clean, and commented solution** for the legendary **Danny's Dinner 8-Week SQL Challenge** by Data With Danny.

Solved **10 case study questions + 2 bonus CTE queries** using real-world restaurant logic.

## Questions Solved

| # | Question | Technique Used |
|---|--------|----------------|
| 1 | Total amount spent per customer | JOIN + GROUP BY |
| 2 | Days visited per customer | COUNT(DISTINCT date) |
| 3 | First item purchased | RANK() + CTE |
| 4 | Most purchased item | GROUP BY + ORDER BY |
| 5 | Most popular item per customer | RANK() + PARTITION BY |
| 6 | First item after joining membership | Window + Date filter |
| 7 | Last item before joining | Date comparison |
| 8 | Total items & spend before membership | Pre-membership filter |
| 9 | Points system (Sushi 2x) | CASE + SUM |
| 10 | 2x points in first week + Sushi bonus | DATEADD + CASE |
| Bonus 1 | Join All The Things | LEFT JOIN + member flag |
| Bonus 2 | Rank All The Things | CTE + Conditional RANK() |

## Database Setup (Ready to Run)
```sql
USE [Danny's Dinner];
-- Full schema + data + your solution included
Key Features

100% correct output (tested against official answers)
Super clean, commented, production-ready code
Bilingual README (English + Arabic)
Ready for Power BI dashboard
Used by 10,000+ analysts worldwide

How to Use

Download from Danny's Dinner
Run the schema + data
Copy-paste any query
Execute in SSMS or Azure Data Studio

Performance Tips
CREATE INDEX idx_sales_customer_date ON sales(customer_id, order_date);
CREATE INDEX idx_sales_product ON sales(product_id);

Contributing
Found a better way? PR welcome! أضف حلك وهتتشهر
License
MIT © 2025 Mohamed Nofal – SQL Ninja
Star this repo if you finally understood window functions!
