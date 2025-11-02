# Kimia Farma Analytics Project (Google BigQuery)

This project analyzes Kimia Farma transaction data using SQL on Google BigQuery.

## Dataset
- **kf_final_transaction**
- **kf_kantor_cabang**
- **kf_product**

## Key Query
See [`kf_query.sql`](./kf_query.sql) for the SQL script that:
- Joins transaction, branch, and product data
- Calculates discount-adjusted prices and profit margins
- Produces the final analytical table (`analisa`)

---

Created as part of a data analytics learning project using BigQuery.
