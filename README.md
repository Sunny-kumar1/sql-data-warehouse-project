# 🚀 Modern Data Warehouse & Analytics Project

> End-to-End Data Warehouse Solution using SQL Server, Medallion Architecture, ETL Pipelines, Dimensional Modeling, and Business Analytics.

---

## 📌 Project Overview

This project demonstrates how to design and build a production-inspired **Data Warehouse** from multiple operational systems using modern data engineering principles.

The solution follows the **Medallion Architecture (Bronze → Silver → Gold)** to transform raw ERP and CRM datasets into a business-ready analytical model that supports reporting, dashboarding, and decision-making.

The project covers the complete data engineering lifecycle:

- Data Ingestion
- Data Cleansing & Transformation
- Data Integration
- Data Modeling
- ETL Development
- Analytics & Reporting

---

## 🏗️ Solution Architecture

<img width="1149" height="561" alt="Data Warehouse Architecture" src="https://github.com/user-attachments/assets/fd073cff-bd61-4a93-94f1-cb7e299ddd5c" />

### Medallion Architecture

### 🥉 Bronze Layer — Raw Data

The Bronze layer stores raw data exactly as received from the source systems.

**Responsibilities**

- Import CSV files
- Preserve source data
- Maintain raw historical structure
- Minimal transformations
- Foundation for downstream processing

---

### 🥈 Silver Layer — Clean & Standardized Data

The Silver layer transforms raw data into clean, validated, and standardized datasets.

**Processes**

- Data cleansing
- Null handling
- Duplicate removal
- Data type conversion
- Standardization
- Data validation
- Business rule implementation

---

### 🥇 Gold Layer — Business Model

The Gold layer contains analytics-ready data modeled using a **Star Schema**.

**Components**

- Fact Tables
- Dimension Tables
- Business KPIs
- Aggregated datasets
- Reporting views

This layer serves as the single source of truth for reporting, BI tools, and business analytics.

---

# 📂 Project Structure

```
Data-Warehouse-Project/
│
├── datasets/
│   ├── crm/
│   └── erp/
│
├── docs/
│   ├── requirements.md
│   ├── architecture.drawio
│   └── data_model.drawio
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│   └── analytics/
│
├── images/
│
├── README.md
└── LICENSE
```

---

# ⚙️ Technologies Used

| Category | Technology |
|-----------|------------|
| Database | SQL Server Express |
| IDE | SQL Server Management Studio (SSMS) |
| ETL | T-SQL |
| Data Modeling | Star Schema |
| Architecture | Medallion Architecture |
| Documentation | Markdown |
| Version Control | Git & GitHub |
| Diagramming | Draw.io |

---

# 📊 Data Pipeline

```
CSV Files (ERP + CRM)
          │
          ▼
Bronze Layer
(Raw Data)
          │
          ▼
Silver Layer
(Cleansed & Standardized)
          │
          ▼
Gold Layer
(Star Schema)
          │
          ▼
Analytics
Dashboards
Business Reports
```

---

# 🎯 Project Objectives

## Data Engineering

- Build a scalable SQL Server data warehouse
- Design Medallion Architecture
- Develop modular ETL pipelines
- Integrate CRM and ERP systems
- Improve data quality
- Create reusable transformation logic

---

## Data Analytics

Generate business insights including:

### 👥 Customer Analytics

- Customer segmentation
- Customer purchasing behavior
- Customer lifetime value
- Top customers

### 📦 Product Analytics

- Best-selling products
- Product revenue
- Category performance
- Product trends

### 💰 Sales Analytics

- Revenue analysis
- Monthly sales trends
- Sales growth
- Order performance
- Regional analysis

---

# ⭐ Data Modeling

The Gold layer follows a **Star Schema** consisting of:

### Dimension Tables

- DimCustomer
- DimProduct
- DimDate

### Fact Tables

- FactSales

This design enables high-performance analytical queries.

---

# 🔄 ETL Workflow

### Extract

- Load ERP CSV files
- Load CRM CSV files

### Transform

- Data cleansing
- Data validation
- Standardization
- Data integration
- Surrogate key generation

### Load

- Bronze Layer
- Silver Layer
- Gold Layer

---

# 📈 Business Insights

The warehouse enables analysis such as:

- Revenue Trends
- Customer Growth
- Product Performance
- Sales Performance
- Top Selling Products
- Customer Segmentation
- Monthly KPIs
- Business Performance Dashboard

---

# 📚 Learning Outcomes

This project demonstrates practical experience with:

- SQL Development
- Data Warehousing
- ETL Pipeline Development
- Data Cleaning
- Data Modeling
- Star Schema Design
- Analytical SQL
- Business Intelligence
- Database Design
- Query Optimization

---

# 🚀 Getting Started

## Prerequisites

- SQL Server Express
- SQL Server Management Studio (SSMS)
- Git
- CSV Dataset

---

## Setup

Clone the repository

```bash
git clone https://github.com/yourusername/Data-Warehouse-Project.git
```

Open the project in **SSMS**.

Execute SQL scripts in the following order:

```
1. Bronze
2. Silver
3. Gold
4. Analytics
```

---

# 📁 Dataset

Source systems:

- CRM
- ERP

Both datasets are provided as CSV files and imported into SQL Server before ETL processing.

---

# 📖 Documentation

The repository includes:

- Project Requirements
- Data Architecture
- ETL Flow
- Data Model
- SQL Scripts
- Analytics Queries

---

# 🌟 Skills Demonstrated

✔ SQL Server

✔ ETL Development

✔ Data Engineering

✔ Data Warehousing

✔ Medallion Architecture

✔ Star Schema

✔ Data Modeling

✔ SQL Analytics

✔ Business Intelligence

✔ Git & GitHub

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and submit a pull request.

---

# 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you found this project useful, consider giving it a Star!
