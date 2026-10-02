# Automating Monthly Business Performance Reports

## Problem Statement

The company receives business transaction data containing information about orders, products, regions, sales channels, salespersons, customers, revenue, costs, discounts, payment methods, and delivery performance.

As business data grows, manually reviewing and preparing monthly performance reports can become time-consuming and repetitive. Raw datasets may also contain missing values, inconsistent data types, invalid entries, and other data-quality issues that need to be addressed before the data can be reliably analyzed.

Without a structured data-cleaning and preparation process, inaccurate or inconsistent data can affect business reporting and make it difficult to identify meaningful performance trends.

The company therefore needs a systematic approach to clean, transform, and prepare its business data so that it can be used for reliable analysis and reporting.

### Key Business Questions

The project is designed to prepare the data for analysis of questions such as:

- How are sales and revenue distributed across products and regions?
- Which sales channels contribute to business performance?
- How are salespersons performing?
- What are the patterns in order status and payment methods?
- How do discounts, revenue, and costs relate to business performance?
- What patterns can be identified in delivery performance?

### Objective

The objective of this project is to develop a **repeatable Python-based data-cleaning and preparation workflow** that transforms a messy business dataset into a structured, analysis-ready dataset.

The cleaned dataset can then be used for further analysis, reporting, and dashboard development.

## Data Preparation Approach

**Problem → Data Understanding → Cleaning → Transformation → Validation → Analysis-Ready Dataset**

The project includes:

- Loading the raw business dataset
- Understanding the dataset structure and data types
- Identifying missing values
- Identifying duplicate records
- Detecting inconsistent and invalid values
- Converting columns to appropriate data types
- Handling numeric and non-numeric values
- Converting date information into a usable format
- Creating additional date-related columns
- Validating the cleaned dataset
- Exporting the final analysis-ready dataset

## Data Cleaning

The original dataset contained **4,000 records and 15 columns**.

During the cleaning process, issues such as the following were identified:

- Missing values
- Invalid numeric values
- Inconsistent data formats
- Invalid date values
- Text values in numeric columns
- Unknown or unavailable values
- Duplicate records

After cleaning and validation, the resulting dataset contains **3,276 records and 19 columns**.

Additional date-related columns were created to support future analysis:

- Order Year
- Order Month
- Order Day
- Order Month Name

## Tools Used

- Python
- Pandas
- NumPy
- Google Colab

## Project Workflow

```text
Raw Data
   ↓
Data Understanding
   ↓
Data Quality Checks
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Data Validation
   ↓
Cleaned Dataset
   ↓
Future Analysis & Visualization
```

## Project Files

The project is organized into the following folders:

```text
python/
├── README.md
├── data/
│   ├── raw_messy_business_performance_4000.csv
│   └── Business_Performance_Dataset_Cleaned.csv
│
├── notebooks/
│   └── Business_Performance_Data_Cleaning.ipynb
│
└── documentation/
    ├── Phase_1_Project_Proposal.pdf
    ├── Phase_2_Data_Understanding_and_Cleaning.pdf
    └── Problem Statement_Automating Monthly Business Performance Reports.pdf
```

## Output

The main output of this project is a **cleaned and structured business performance dataset** that can be used as the foundation for further data analysis and visualization.

The cleaned dataset can also be used in tools such as Excel, Tableau, or Power BI for further reporting and dashboard development.

## Future Scope

The cleaned dataset provides a foundation for further analysis, including:

- Exploratory Data Analysis
- Business performance trends
- Product and regional analysis
- Sales channel analysis
- Revenue and cost analysis
- Delivery performance analysis
- Interactive dashboards

---

**Project:** Automating Monthly Business Performance Reports  
**Focus:** Data Cleaning, Data Preparation & Business Analysis  
**Tools:** Python, Pandas, NumPy, Google Colab
