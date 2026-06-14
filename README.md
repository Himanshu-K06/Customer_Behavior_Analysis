# Customer Shopping Behavior Data Analysis
This repository contains an end-to-end data analytics project focused on a retail company's customer shopping behavior dataset. The project demonstrates a professional corporate-style workflow, moving from raw data processing to actionable business insights.

## Project Overview
The goal of this project is to analyze customer purchasing patterns to help management improve sales, customer satisfaction, and loyalty. By applying industry-standard tools, we transform a raw dataset into a dynamic, interactive dashboard and a professional presentation.

## Workflow & Technical Steps

### 1. Data Cleaning & Preparation (Python)
Using the *pandas* library, the raw dataset was processed to ensure quality and consistency:
*   **Exploratory Data Analysis (EDA):** Performed initial inspections to understand data structure and missing values.
*   **Data Imputation:** Filled missing *review_rating* values by calculating the median rating per category, preventing bias.
*   **Data Standardization:** Converted column names to consistent *snake_case* to facilitate smooth SQL querying.
*   **Feature Engineering:** Created an *age_group* category for better demographic analysis and converted text-based purchase frequencies into numeric values.
*   **Redundancy Removal:** Identified and dropped redundant columns that carried duplicate information.

### 2. Business Analysis (SQL)
Data was migrated to *PostgreSQL* to conduct advanced analytical tasks:
*   **Revenue Analysis:** Calculated revenue metrics split by demographics and shipping types.
*   **Segmentation:** Used `CASE` statements and Common Table Expressions (CTEs) to segment customers into *new*, *returning*, and *loyal* groups.
*   **Window Functions:** Applied `ROW_NUMBER()` to extract the top-performing products across various categories.
*   **Subqueries:** Executed advanced queries to identify specific customer behaviors, such as spend thresholds during promotional periods.

### 3. Visualization & Dashboarding (Power BI)
An interactive dashboard was developed to track Key Performance Indicators (KPIs):
*   **Measures:** Created custom DAX measures for total customer count, average spend, and review ratings.
*   **Visuals:** Integrated donut charts, clustered columns, and bar charts for intuitive data storytelling.
*   **Interactivity:** Implemented slicers (subscription status, gender, category, shipping type) to allow stakeholders to filter data dynamically.

### 4. Documentation & Reporting
*   **Report Generation:** Created a comprehensive project report documenting the entire methodology.
*   **AI-Powered Presentation:** Utilized *Gamma AI* to convert the technical report into a professional slide deck for executive stakeholders.

## Acknowledgments
This project serves as a portfolio piece showcasing how data analysts bridge the gap between raw data and business decision-making.
