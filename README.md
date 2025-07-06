# 🏨 Strategy Analytics Project – SQL Data Management for Hotel Operations

This project delivers a **data management system** for Safe Space Hotels, designed to optimize operations, evaluate branch performance, and improve customer loyalty. Built using **SQL and SQLite**, the system integrates synthetic datasets and generates actionable insights through advanced querying and visualization.  

Developed as part of the *Data Management* module at Warwick Business School, this project demonstrates end-to-end data engineering and analytics capabilities.  

---

## 📂 Repository Contents

| File                                 | Description                                                                                     |
|--------------------------------------|-------------------------------------------------------------------------------------------------|
| `DM_Group_5.pdf`                     | Full project report including database design, SQL implementation, and business analysis.       |

---

## 📝 Project Overview

- **Business Context**: Safe Space Hotels operates multiple properties across the UK and requires an integrated database to monitor:
  - Branch revenue performance.
  - Employee analysis and turnover rates.
  - Customer satisfaction and loyalty.  
- **Key Features**:
  - Designed an **ER diagram** and relational schema with 10+ interconnected tables.  
  - Generated synthetic data (2,000+ records) for realistic analysis.  
  - Built SQL queries for business-critical insights (e.g., revenue trends, staff allocation, satisfaction drivers).  

---

## 🛠️ Tools & Techniques
- **Database**: SQLite  
- **Query Language**: SQL (DDL & DML)  
- **Data Engineering**: Synthetic data generation using Python  
- **Visualization**: Plots for revenue, salary comparisons, and satisfaction metrics  

---

## 📊 Results & Insights

| Metric                         | Insight                                                                                  |
|---------------------------------|------------------------------------------------------------------------------------------|
| **Top Performing Branch**      | London branch contributed ~49% of total revenue with premium pricing strategies.         |
| **Employee Cost Analysis**     | Identified salary inefficiencies in Southampton branch impacting financial performance.  |
| **Customer Satisfaction**      | Gold membership correlated with highest satisfaction scores across all branches.         |

- Recommended targeted marketing for loyalty programs and cost optimization for staff distribution.

---

## 📁 File Descriptions

### `DM_Group_5.pdf`
- Contains:
  - ER diagrams and logical schema design.  
  - SQL schema creation queries and sample data generation process.  
  - Analysis of branch revenue, employee turnover, and customer satisfaction.  

---

### `WhatsApp Video 2025-03-19 at.mp4`
- Presentation explaining:
  - Project goals and database structure.  
  - Key SQL queries for business insights.  
  - Actionable recommendations for Safe Space Hotels.  

---

### `hotel_db.sqlite` (if included)
- SQLite database file containing:
  - Tables: SITE, HOTEL, ROOM, CUSTOMER, BOOKING, EMPLOYEE, CONTRACT, PAYMENT, REVIEW, HOTEL_FACILITY.  
  - Populated synthetic data for querying and reporting.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/aarushidhaka/Strategy-Analytics-Project-SQL-Data-Management-for-Hotel-Operations.git
   cd hotel-sql-data-management
