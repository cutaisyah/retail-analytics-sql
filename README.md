# Retail Analytics SQL

This project is a **retail data analytics** capstone using **PostgreSQL** and **SQL queries**.  
It analyzes transactions, products, users, and reviews from a sample e-commerce dataset.

---

## Project Structure
.
├── .gitignore
├── docker-compose.yml # PostgreSQL + Adminer setup
├── pgdata_purwadika/ # Postgres data volume (ignored)
├── sql_dump/ # Optional: SQL dump files
└── Retail_Analytics.ipynb # Jupyter Notebook with SQL queries and results

## Key Features

- Compute total orders, total sales, and top products with discounts
- Analyze sales per product category using **CTE**
- Analyze products and reviews based on rating
- Analyze users (email domain, birth year, source)
- Use **CTE** and **window functions** (ROW_NUMBER, PARTITION BY) for advanced queries
- Exported results and summaries in a **Jupyter Notebook**