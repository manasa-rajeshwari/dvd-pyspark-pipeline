# 🎬 DVD Rental Batch Data Pipeline (PySpark)

## 📌 Overview
This project demonstrates a batch data pipeline built using PySpark to process the PostgreSQL dvdrental dataset. The pipeline extracts raw data, performs transformations, and generates analytical datasets for business insights.

---

## 🚀 Tech Stack
- PySpark
- PostgreSQL
- JDBC
- Python
- VSCode / Jupyter Notebook

---

## 🧱 Architecture
PostgreSQL → PySpark → CSV Data Lake

---

## 📊 Use Cases
- Customer revenue analysis
- Top-performing movies
- Rental trends over time

---

## ⚙️ Pipeline Steps

### 1. Extract
- Connected to PostgreSQL using JDBC
- Loaded tables: customer, rental, payment, film, inventory

### 2. Transform
- Aggregated total spend per customer
- Joined datasets for enriched customer insights
- Computed movie revenue rankings
- Generated daily rental trends

### 3. Load
- Exported results into CSV format
- Optimized output using coalesce(1)

---

## 📁 Project Structure
