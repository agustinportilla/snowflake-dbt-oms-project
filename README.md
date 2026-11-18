# Snowflake & dbt – Order Management System (OMS)

## Project Overview

This project focuses on building a data transformation workflow for an Order Management System (OMS) using **Snowflake, dbt, SQL, and GitHub**.

The objective is to transform raw operational data into structured and analytics-ready datasets following data engineering and data modeling best practices.

The project covers data organization, SQL transformations, modular data modeling, and version control.

## Technologies

- **Snowflake:** Cloud data warehouse.
- **dbt:** Data transformation and modeling.
- **SQL:** Data manipulation and transformation.
- **Git & GitHub:** Version control and source code management.

## Data Model

The project uses an Order Management System dataset containing information about:

- Customers
- Orders
- Order Items
- Products
- Suppliers
- Stores
- Employees
- Dates

## Project Structure

```text
snowflake-dbt-oms-project/
│
├── analyses/
├── macros/
├── models/
│   ├── staging/
│   └── serving/
├── seeds/
├── snapshots/
├── tests/
│
├── .gitignore
├── dbt_project.yml
└── README.md
```

## Data Transformation Workflow

The project follows a structured transformation approach:

1. **Landing Layer:** Stores the original source tables in Snowflake.
2. **Staging Layer:** Applies initial transformations, standardizes fields, and prepares source data for downstream models.
3. **Serving Layer:** Organizes transformed datasets for analytical consumption.

## dbt Features

The project incorporates dbt capabilities such as:

- Modular SQL models.
- Model dependencies and materializations.
- Data testing and quality checks.
- Reusable macros.
- Source definitions and documentation.

## Project Goals

- Develop practical Data Engineering skills.
- Implement scalable data transformation workflows.
- Apply data modeling best practices.
- Integrate Snowflake with GitHub for version control.
- Build a foundation for analytics-ready datasets.

---

**Project Status:** In Development
