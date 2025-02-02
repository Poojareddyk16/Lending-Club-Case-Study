# Lending Club Case Study

A comprehensive data analysis project aimed at identifying patterns, trends, and risk factors in Lending Club loan data. This case study leverages Python for data cleaning, exploratory data analysis (EDA), and visualization to derive actionable insights into loan defaults and customer behavior.

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Dataset](#dataset)
- [Features](#features)
- [Tools and Technologies](#tools-and-technologies)
- [Analysis Workflow](#analysis-workflow)
- [Key Insights](#key-insights)
- [How to Run the Code](#how-to-run-the-code)
- [Folder Structure](#folder-structure)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## Project Overview
The Lending Club Case Study focuses on analyzing loan data to assess borrower profiles, identify high-risk customers, and understand factors contributing to loan defaults. The insights derived from this study can help financial institutions improve their risk assessment processes and optimize lending strategies.

---

## Objective
The primary objectives of this case study are:
1. To analyze the characteristics of borrowers who are likely to default.
2. To identify key factors that influence loan repayment behavior.
3. To provide actionable recommendations for improving the lending process.

---

## Dataset
The dataset used in this case study is publicly available Lending Club loan data. It contains information about loans issued by Lending Club, including borrower details, loan amounts, interest rates, repayment status, and more.

### Key Attributes:
- **Loan Amount**: The total amount borrowed.
- **Interest Rate**: The annual interest rate applied to the loan.
- **Loan Status**: Whether the loan is fully paid, charged off, or current.
- **Debt-to-Income Ratio (DTI)**: A measure of a borrower's financial health.
- **Annual Income**: The annual income of the borrower.
- **Purpose**: The stated purpose of the loan (e.g., debt consolidation, home improvement).

---

## Features
1. **Data Cleaning**:
   - Handled missing values, outliers, and inconsistencies in the dataset.
   - Standardized categorical variables for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed distributions of key variables like loan amount, interest rates, and annual income.
   - Examined correlations between borrower characteristics and loan defaults.

3. **Visualization**:
   - Created insightful plots using Matplotlib and Seaborn to highlight trends and patterns.
   - Visualized default rates across different borrower profiles.

4. **Risk Segmentation**:
   - Segmented borrowers based on risk factors such as credit score, DTI ratio, and income levels.

---

## Tools and Technologies
The following tools were used in this project:
- **Python**: Core programming language for data analysis.
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook**: For interactive analysis and visualization.
- **Excel/CSV Files**: Input data format for analysis.

---

## Analysis Workflow
1. **Data Loading**:
   - Imported the dataset into a Pandas DataFrame for processing.

2. **Data Cleaning**:
   - Removed irrelevant columns and rows with excessive missing values.
   - Imputed missing values where appropriate.

3. **EDA**:
   - Performed univariate and bivariate analyses to understand variable distributions.
   - Explored relationships between borrower attributes (e.g., income level) and loan status.

4. **Visualization**:
   - Plotted default rates by purpose of loans using bar charts.
   - Analyzed the impact of interest rates on repayment behavior using scatter plots.

5. **Segmentation**:
   - Grouped borrowers into risk categories based on key metrics like DTI ratio and credit score.

---

## Key Insights
1. Borrowers with higher debt-to-income ratios are more likely to default on loans.
2. Loans taken for purposes such as "small business" or "renewable energy" have higher default rates compared to "debt consolidation" or "home improvement."
3. Interest rates above 15% correlate strongly with an increased likelihood of default.
4. Annual income plays a significant role in determining a borrower's ability to repay loans.

---

## How to Run the Code
1. Clone this repository: 
```
git clone https://github.com/Poojareddyk16/Lending-Club-Case-Study.git <br>
cd Lending-Club-Case-Study
```

2. Install required Python libraries:
```
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open the Jupyter Notebook:
```
jupyter notebook lending_club_analysis.ipynb
```

4. Run all cells sequentially to reproduce the analysis and visualizations.

---

## Folder Structure
```
Lending-Club-Case-Study/
│
├── data/
│ └── lending_club_data.csv # Raw dataset used for analysis
│
├── notebooks/
│ └── lending_club_analysis.ipynb # Jupyter notebook with code & analysis
│
├── outputs/
│ └── visualizations/ # Saved plots from EDA
│
└── README.md # Project documentation (this file)
```


---

## Future Enhancements
1. Implement machine learning models (e.g., logistic regression) to predict loan defaults.
2. Add advanced visualizations using Tableau or Power BI for interactive dashboards.
3. Explore time-series analysis for trends in default rates over time.

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.
