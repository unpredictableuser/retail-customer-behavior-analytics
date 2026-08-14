# Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, from loading and exploring raw data to creating SQL insights, an interactive Power BI dashboard, a written report, and a presentation.

The project focuses on transforming raw data into meaningful business insights using **Python, SQL, Power BI, and Gamma**.

## Dataset

The dataset is loaded and analyzed using Python. It contains structured records that can be used to identify trends, patterns, relationships, and key business metrics.

Typical preparation includes:

* Understanding the dataset structure and columns
* Checking data types and missing values
* Identifying duplicates and inconsistent records
* Detecting outliers and invalid values
* Cleaning and transforming data for analysis
* Preparing the final dataset for SQL and dashboard development

> **Note:** Replace this section with the dataset name, source, number of rows/columns, and a brief description of the business problem.

## Tools & Technologies

| Tool                                | Purpose                                        |
| ----------------------------------- | ---------------------------------------------- |
| **Python**                          | Data loading, EDA, cleaning, and preprocessing |
| **Pandas**                          | Data manipulation and analysis                 |
| **NumPy**                           | Numerical operations                           |
| **Matplotlib / Seaborn**            | Data visualization during EDA                  |
| **PostgreSQL / MySQL / SQL Server** | SQL-based data analysis                        |
| **Power BI**                        | Interactive dashboard and visualization        |
| **Gamma**                           | Presentation/PPT creation                      |
| **Jupyter Notebook**                | Python-based analysis and documentation        |

## Project Steps

### 1. Load the Dataset

The dataset is imported into Python using Pandas.

The initial analysis includes:

* Reviewing dataset dimensions
* Inspecting column names and data types
* Viewing sample records
* Checking missing values
* Understanding categorical and numerical variables

### 2. Exploratory Data Analysis (EDA)

EDA is performed to understand the underlying patterns and characteristics of the data.

Key activities include:

* Descriptive statistics
* Missing-value analysis
* Duplicate detection
* Distribution analysis
* Correlation analysis
* Outlier identification
* Trend and category analysis
* Visual exploration using charts

### 3. Data Cleaning

The raw dataset is cleaned and prepared for further analysis.

Major tasks include:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing inconsistent values
* Treating invalid records and outliers where appropriate
* Creating derived columns when required

The cleaned dataset is then exported for SQL analysis and dashboard development.

### 4. SQL Analysis

The cleaned data is loaded into a relational database such as **PostgreSQL, MySQL, or SQL Server**.

SQL queries are used to answer business-related questions and generate analytical insights.

Examples include:

* Aggregations using `SUM`, `AVG`, `COUNT`, and `MAX/MIN`
* Grouping and filtering
* `JOIN` operations
* Subqueries and CTEs
* Window functions
* Ranking and trend analysis
* KPI calculations

The SQL analysis provides a structured way to validate findings and extract business insights from the dataset.

### 5. Power BI Dashboard

The cleaned/processed data is connected to Power BI to create an interactive dashboard.

The dashboard may include:

* KPI cards
* Trend charts
* Category comparisons
* Geographic or segment analysis
* Interactive filters and slicers
* Tables and detailed views

The dashboard is designed to provide a clear overview of important business metrics and allow users to explore the data interactively.

## Dashboard

The Power BI dashboard presents the key findings from the analysis in an easy-to-understand format.

**Dashboard highlights:**

* Key performance indicators
* Important trends and patterns
* Top-performing and underperforming categories
* Comparative analysis
* Interactive filtering
* Business-focused visualizations

Add a screenshot of the completed Power BI dashboard here:

```text
![Power BI Dashboard](images/dashboard.png)
```

## Results & Insights

The analysis converts the raw dataset into actionable insights.

Key outcomes include:

* Identified important trends and patterns in the data
* Determined major factors affecting key metrics
* Used SQL to answer business questions efficiently
* Built an interactive Power BI dashboard
* Summarized findings in a professional analytical report
* Created a presentation using Gamma to communicate the results

> **Tip:** Add 3–5 specific findings from your project here, preferably supported by numbers or percentages.

## Project Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── EDA_and_Data_Cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── analytics_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

## How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>
cd data-analytics-project
```

### 2. Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run `EDA_and_Data_Cleaning.ipynb` to load, explore, clean, and prepare the dataset.

### 4. Run SQL Analysis

1. Set up PostgreSQL, MySQL, or SQL Server.
2. Import the cleaned dataset.
3. Open `analysis_queries.sql`.
4. Execute the queries using your preferred database client.

### 5. Open the Power BI Dashboard

Open the `.pbix` file in **Power BI Desktop**.

Update the data source if required and refresh the dashboard.

### 6. Review the Report & Presentation

The final analytical report and Gamma-generated presentation are available in the `report/` and `presentation/` directories.

## Key Skills Demonstrated

* Python for Data Analysis
* Exploratory Data Analysis
* Data Cleaning & Preprocessing
* SQL Querying
* Relational Database Analysis
* Data Visualization
* Power BI Dashboard Development
* Business Intelligence
* Data Storytelling
* Analytical Reporting
* Presentation Development

## Conclusion

This project demonstrates a complete **data-to-insight workflow**, combining Python, SQL, Power BI, and presentation tools to analyze data and communicate business findings effectively.

It showcases practical skills in **data preparation, analytical thinking, SQL, visualization, dashboard development, and business storytelling**.

