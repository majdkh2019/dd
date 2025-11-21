# Employee Attrition Analysis – Final Project

This project analyzes **employee attrition** using data extracted from an SQL database.  
The notebook performs **data integration**, **exploratory data analysis (EDA)**, **visualization**, and **key factor identification** related to employee turnover.

## Project Structure
- finalproject.ipynb — Main notebook
- joined_employee_data.csv — Generated cleaned dataset

## 1. Data Sources
Two SQL tables are loaded and joined:
- table1 — Employee base info
- table2 — Additional employee attributes

## 2. Data Integration
Using SQLAlchemy:
- Connect to MSSQL database
- Load both tables into pandas
- Perform INNER JOIN
- Export merged dataset

## 3. Exploratory Data Analysis (EDA)
Includes:
- Dimensions + data types
- Missing values check
- Statistical summary
- Correlation analysis
- Visualizations (histograms, boxplots, heatmaps, scatterplots)

## 4. Attrition-Focused Analysis
Analyzes:
- Department attrition
- Salary impact
- Age impact
- Overtime effect
- Job satisfaction

## 5. Visualizations
Generated:
- Distribution plots
- Bar charts
- Heatmaps
- Attrition rate comparisons

## 6. Output Files
- joined_employee_data.csv — Clean combined dataset

## 7. How to Run
Install dependencies:
```
pip install pandas sqlalchemy matplotlib seaborn pyodbc
```

Run the notebook:
```
jupyter notebook finalproject.ipynb
```

## 8. Future Improvements
- Attrition prediction model  
- Dashboard (PowerBI / Tableau / Streamlit)  
- Advanced feature engineering  
- Automated SQL pipeline  

## Author
Majd Lh — Final Project for Employee Attrition Analysis
