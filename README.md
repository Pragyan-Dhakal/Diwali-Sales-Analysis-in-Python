# Diwali Sales Analysis

## Festive Season Retail Insights

Welcome to the **Diwali Sales Analysis** repository! This project explores sales trends, consumer demographics, and product performance during the Diwali festival season through comprehensive data analysis and visualization.

---

## Table of Contents

- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Consumer Demographics](#consumer-demographics)
    - [Gender Insights](#gender-insights)
    - [Age Group Distribution](#age-group-distribution)
    - [Marital Status](#marital-status)
    - [Occupation](#occupation)
  - [Geographic Distribution](#geographic-distribution)
  - [Product Category Performance](#product-category-performance)
  - [Top Selling Products](#top-selling-products)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Author](#author)

---

## Project Structure

```bash
├── Diwali Sales Data.csv        # Raw Diwali sales dataset
├── Diwali Sales Analysis.ipynb  # Jupyter Notebook with full EDA
└── README.md                    # Project overview and instructions
```

## Dataset

The `Diwali Sales Data.csv` contains transactional records with fields such as:
- `Transaction_ID`
- `Gender`
- `Age`
- `State`
- `Marital_Status`
- `Occupation`
- `Product_Category`
- `Amount`

All analyses derive from these variables.

## Installation

```bash
pip install pandas numpy matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
[git clone https://github.com/pragyandhakal/diwali-sales-analysis.git](https://github.com/Pragyan-Dhakal/Diwali-Sales-Analysis-in-Python.git)
   cd diwali-sales-analysis
   ```
2. Open the notebook:
   ```bash
   jupyter notebook "Diwali Sales Analysis.ipynb"
   ```
3. Follow the steps to reproduce the analysis.

## Exploratory Data Analysis

### Consumer Demographics
- **Gender Insights:** Analysis of purchase distribution and spend by gender.
- **Age Group Distribution:** Visualization of sales across different age brackets.
- **Marital Status:** Comparison of spending patterns between married and unmarried shoppers.
- **Occupation:** Identification of top buyer occupations.

### Geographic Distribution
- **State-wise Sales:** Mapping of sales volume and revenue by state.

### Product Category Performance
- Breakdown of transaction counts and total sales by product category.

### Top Selling Products
- Highlighting the highest-selling items by count and revenue contribution.

## Conclusion

This Diwali Sales Analysis uncovers key insights on shopper demographics, regional hotspots, and product trends. Retailers can leverage these findings for targeted marketing, inventory planning, and strategic promotions in future festive seasons.

## Technologies Used

- Python 3.7+  
- Pandas, NumPy for data wrangling  
- Matplotlib, Seaborn for visualization

## Author

**Pragyan Dhakal** – Data Analyst & Retail Strategy Enthusiast

