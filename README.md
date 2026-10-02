# Excel Data Analysis – World's Billionaires

## 📊 Project Overview

This project is an **Excel-based data cleaning and analysis project** using a dataset of billionaires and their financial, demographic, and country-level information.

The project focuses on cleaning raw data, creating useful calculated fields, analyzing the data with PivotTables, and presenting the results through interactive filtering and visualization.

## 🎯 Project Objectives

- Clean and prepare the raw dataset for analysis
- Standardize inconsistent data values
- Calculate age from date of birth information
- Convert financial/economic values into appropriate number formats
- Identify the top 10 richest people in the dataset
- Use PivotTables and slicers for interactive analysis
- Present findings using a bar chart

## 🛠️ Tools Used

- **Microsoft Excel**
- Data Cleaning
- Excel Formulas
- PivotTables
- Slicers
- Bar Chart
- Data Formatting

## 🧹 Data Cleaning

The raw dataset was cleaned before performing the analysis.

### Cleaning steps performed:

1. **Removed duplicate records**
2. **Standardized gender values**
   - Changed `MS` to `Male`
   - Changed `FS` to `Female`
3. **Calculated Age**
   - Used the available birth year, birth month, and birth day to create the birth date
   - Calculated the current age from the birth date
   - Removed decimal values from age for easier analysis
4. **Formatted GDP values**
   - Converted GDP country values into a proper number format
   - Removed unnecessary decimal values
5. Checked and organized the dataset so it could be used effectively for analysis.

## 🔍 Data Analysis

After cleaning the data, Excel PivotTables were used to analyze the dataset.

### Top 10 Richest People

A PivotTable was created to identify the **Top 10 richest people** based on their `finalWorth`.

The analysis sheet contains the summarized results, including:

- Person name
- Total final worth

The current analysis identifies:

1. Bernard Arnault & family
2. Elon Musk
3. Jeff Bezos
4. Larry Ellison
5. Warren Buffett
6. Bill Gates
7. Michael Bloomberg
8. Carlos Slim Helu
9. Mukesh Ambani
10. Steve Ballmer

> The ranking reflects the values available in the project dataset and should not be treated as a current real-world billionaire ranking.

## 🎛️ Interactive Analysis

### Slicers

Slicers were added to make the PivotTable analysis more interactive.

They allow the user to filter the data and explore the results based on the available categories in the workbook.

## 📈 Data Visualization

A **Bar Chart** was created to visually represent the Top 10 richest people and compare their final worth.

The visualization makes it easier to:

- Compare billionaire wealth
- Identify the highest values
- Understand the difference between the top entries
- Present the analysis in a simple visual format

## 📁 Project Structure

```text
Excel-Data-Analysis/
│
├── EXCEL_analysis.xlsx
└── README.md
```

### Workbook Sheets

**Data**
- Contains the cleaned dataset
- Includes calculated fields such as Age, Current Date, Birth Date, and Age Decimal

**analysis**
- Contains the PivotTable analysis
- Top 10 richest people summary
- Bar chart visualization
- Interactive analysis elements

## 💡 Key Skills Demonstrated

Through this project, I practiced:

- Data Cleaning in Excel
- Removing Duplicates
- Find & Replace
- Data Standardization
- Date Functions
- Age Calculation
- Number Formatting
- PivotTables
- Slicers
- Data Visualization
- Basic Data Analysis

## 🚀 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Standardization
     ↓
Age Calculation
     ↓
Number Formatting
     ↓
PivotTable Analysis
     ↓
Slicers
     ↓
Bar Chart Visualization
     ↓
Insights
```

## 📌 Conclusion

This project demonstrates how Microsoft Excel can be used to transform a raw dataset into a structured and visual analysis.

The workflow covers the important stages of a basic data analysis process: **cleaning → transformation → analysis → visualization**.
