# SSAS Tabular Analytical Model

## Project Overview

Built an analytical solution using a **SQL Server Data Warehouse** connected to an **SSAS Tabular Model**. The project focuses on analytical modeling, DAX-based calculations, and business reporting using Power BI.

The solution demonstrates how data can flow from a SQL Server Data Warehouse into **SQL Server Analysis Services (SSAS) Tabular**, where relationships, hierarchies, and DAX measures are created to provide consistent and reusable analytical data for reporting.

## Architecture

**SQL Server Data Warehouse → SSAS Tabular Model → Power BI**

* **SQL Server Data Warehouse:** Stores structured and transformed business data using a dimensional model.
* **SSAS Tabular:** Provides the semantic/analytical layer with relationships, hierarchies, and DAX measures.
* **Power BI:** Connects to the SSAS Tabular model for reporting, visualization, and analysis.

## Key Components

### 1. SQL Server Data Warehouse

* Designed a dimensional data model using fact and dimension tables.
* Prepared structured data for analytical consumption.
* Created relationships between fact and dimension tables.

### 2. SSAS Tabular Model

* Connected the SQL Server Data Warehouse to SSAS.
* Created tables, relationships, and hierarchies.
* Defined business-friendly measures using **DAX**.
* Implemented calculations required for analytical reporting.
* Explored SSAS Tabular modeling and processing concepts.

### 3. DAX Measures

Created reusable measures for business analysis, such as:

* Total Sales
* Total Quantity
* Average Sales
* Total Customers
* Year-over-Year Analysis
* Percentage and aggregation-based calculations

### 4. Power BI Reporting

* Connected Power BI to the SSAS Tabular model.
* Used SSAS measures for reporting and visualization.
* Built reports to analyze business performance and trends.

## Data Flow

```text
Source Data
    ↓
SQL Server Data Warehouse
    ↓
Dimensional Model
(Fact + Dimension Tables)
    ↓
SSAS Tabular Model
    ↓
Relationships + Hierarchies + DAX Measures
    ↓
Power BI
    ↓
Reports & Business Analysis
```

## Technologies Used

* **Microsoft SQL Server**
* **SQL Server Analysis Services (SSAS) Tabular**
* **DAX**
* **Power BI**
* **SQL**
* **Data Warehousing**
* **Dimensional Modeling**

## Project Objective

The objective of this project is to gain hands-on experience with **SSAS Tabular**, understand how a semantic model is built on top of a SQL Server Data Warehouse, create reusable DAX measures, and consume the analytical model through Power BI.

## Key Learning

Through this project, I gained practical understanding of:

* SSAS Tabular architecture
* Dimensional modeling
* Fact and dimension relationships
* Tabular relationships and hierarchies
* DAX measures
* Analytical/semantic modeling
* Power BI connectivity with SSAS
* Data warehouse to semantic model data flow
* Concepts involved in processing and deploying SSAS models
****
