# Sales Data Analysis

This project conducts an **Exploratory Data Analysis (EDA)** on a sales dataset to extract meaningful insights related to customer demographics and purchasing behavior. The analysis primarily focuses on gender, age group, and product categories to support data-driven business decisions.

##  Objective
To understand:
- Who are the primary buyers?
- Which age group spends the most?
- What product categories are most profitable?
- How demographic factors affect sales?

##  Dataset
The dataset used is `Sales_Data.csv` and includes:
- Gender
- Age group
- Marital status
- Product category
- Purchase amount
- Location data

##  Tools & Libraries
- **Python**
  - pandas
  - numpy
  - matplotlib
  - seaborn
- **Jupyter Notebook**

##  Key Insights
- Most buyers are **females**.
- The **26–35 years** age group shows the highest purchasing activity.
- Specific product categories and customer segments are more profitable.
- Cleaning steps involved dropping unnecessary columns such as `Status` and `unnamed1`.

##  Project Structure
```
Sales_Data_Analysis.ipynb    # Main notebook with analysis & plots
Sales_Data.csv               # Sales dataset
README.md                    # Project documentation
```

##  Getting Started

### Clone the Repository
```bash
git clone https://github.com/yourusername/sales-data-analysis.git
cd sales-data-analysis
```

### Launch the Notebook
```bash
jupyter notebook Sales_Data_Analysis.ipynb
```

Make sure `Sales_Data.csv` is in the same directory as the notebook.
