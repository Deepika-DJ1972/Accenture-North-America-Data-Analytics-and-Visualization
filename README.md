# Accenture North America Data Analytics and Visualization

## Project Overview

This project is part of the **Accenture North America** job simulation focused on advising a hypothetical client regarding content performance. The goal was to clean, merge, and model the data to uncover insights that inform content strategy and help answer the business questions. The process included data cleaning, data modeling, and analysis of content performance.

## Key Steps in the Process

### 1. **Data Cleaning**

The first step in the analysis was **data cleaning**. This process involved several essential tasks to ensure that the dataset was in a usable format for further analysis:

- **Removed Rows with Missing Values**: Rows containing missing or null values were removed to ensure that the dataset was complete and would not skew the analysis results.
  
- **Data Type Transformation**: Certain columns required data type conversion to align with the analysis needs. For example, changing dates from string format to datetime, converting numerical data to integers or floats where necessary.

- **Removal of Irrelevant Columns**: Columns that were not directly relevant to the business question were removed. This step ensured that the analysis focused on the most valuable information, leading to better insights and decisions. For example, any columns unrelated to content performance metrics, like internal identifiers or irrelevant descriptions, were excluded.

- **Consideration of Business Relevance**: Throughout the cleaning process, each column was evaluated for its relevance to the key business question: identifying top-performing content categories. If a column did not seem to contribute to this analysis, it was excluded from the final dataset.

### 2. **Data Modeling**

Once the dataset was cleaned, the next step was to model the data to create useful insights for the business. 

- **Merging Tables**: 
  - The final dataset was created by merging three tables: **Reaction**, **Content**, and **Reaction Types**. 
  - **Reaction table** served as the base, and the relevant columns from the **Content** and **Reaction Types** datasets were joined.
  - This was achieved using the **VLOOKUP** formula in Excel to ensure the datasets aligned correctly.

- **Identifying Top-Performing Categories**:
  - To uncover the top 5 performing categories, the total scores for each category were calculated.
  - The **SUMIF** formula was used to sum the scores for each category based on their content performance, helping to identify the most successful categories based on user reactions.

### 3. **Presentation of Insights**

The final part of the simulation was to present the analysis in a structured format. The agenda for the presentation covered:

- **Agenda**: The presentation covered the key steps taken during the project, including the data cleaning process, the analysis performed, and the resulting insights.

- **Project Recap**: A brief recap of the business problem we aimed to solve: determining the top-performing content categories based on user reactions.

- **Problem**: The problem was to identify which content categories were driving the most engagement, helping the client optimize their content strategy.

- **The Analytics Team**: The team for this analysis consisted of:
  - **Andrew Fleming** (Chief Technical Architect)
  - **Marcus Rompton** (Senior Principle)
  - **Yourself** (Data Analyst)

- **Process**: The analysis process involved:
  - Data cleaning (removal of missing values, conversion of data types, and removal of irrelevant columns).
  - Merging data from multiple tables (using **VLOOKUP**).
  - Performing analysis to find the top-performing content categories using the **SUMIF** formula.

## Conclusion

By the end of the project, we were able to identify the top-performing categories, providing valuable insights that could be used to optimize content strategy. The clean and merged dataset enabled us to perform further analyses that contributed to answering the key business questions effectively.
