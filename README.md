# Customer Churn Analysis

## Project Overview
Customer Churn Analysis is a data analytics project that focuses on understanding customer behavior and identifying the factors responsible for customer churn.

The project uses Python, Pandas, NumPy, and SQLite to clean, transform, and analyze customer data to generate meaningful business insights.

## Objectives
- Understand customer churn patterns.
- Identify factors affecting customer retention.
- Analyze customer demographics and subscription details.
- Explore customer behavior and support interactions.
- Generate insights to help businesses reduce customer churn.

## Tools & Technologies
- **Python** – Data analysis
- **Pandas & NumPy** – Data cleaning and manipulation
- **SQLite3** – Database management and SQL queries
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Development environment

## Analysis Performed

1. **Data Extraction:** Connected SQLite database with Python and extracted data into Pandas DataFrames.

2. **Data Cleaning:** Handled missing values, removed unnecessary columns, corrected data types, and standardized categorical values.

3. **Data Transformation:** Prepared and transformed customer, subscription, and support datasets for analysis.

4. **Exploratory Data Analysis (EDA):**
   - Analyzed overall customer churn.
   - Examined customer demographics.
   - Compared churn across subscription plans.
   - Explored geographical customer distribution.
   - Analyzed customer support and satisfaction information.
   - Identified patterns in customer retention.

5. **Data Visualization:** Used Matplotlib and Seaborn to visualize customer trends and churn patterns.

## Key Insights
- Analyzed the overall customer churn rate.
- Explored customer segments with different churn patterns.
- Examined the relationship between subscription plans and churn.
- Investigated customer support and satisfaction factors.
- Identified areas where customer retention strategies could be improved.

## Project Structure

```text
Churn_Analysis/
│
├── churn_analysis.ipynb
├── customer_churn.db
├── customer_churn_data_raw.xlsx
├── exported_churn_data.csv
├── test_database.sqlite
└── README.md
```

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/nishant1800/Churn_Analysis.git
   ```

2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run `churn_analysis.ipynb`.

## Conclusion
This project provides insights into customer churn through data cleaning, SQL queries, exploratory data analysis, and visualization. The findings can help businesses understand customer behavior and develop effective customer retention strategies.

## Author
**Nishant**

- GitHub: [nishant1800](https://github.com/nishant1800)
- LinkedIn: [Nishant Ranjan](https://www.linkedin.com/in/nishant1800/)