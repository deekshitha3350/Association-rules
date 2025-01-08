# Association-rules
# Association Rule Mining - Customer Purchasing Behavior Analysis

This repository contains an analysis of customer purchasing behavior using **Association Rule Mining** with the **Apriori algorithm**. The goal is to identify frequently purchased product combinations and generate association rules to understand relationships between products. These insights can be used for targeted marketing, product bundling, and promotional strategies.

## Project Overview

In this project, we perform the following steps:

1. **Data Preprocessing:**
   - Load and clean the "Online retail" dataset.
   - Perform data exploration by checking for missing values, duplicates, and basic statistics.

2. **Transaction Data Preparation:**
   - Convert the dataset into transaction format suitable for the Apriori algorithm.
   - Use the `TransactionEncoder` from the `mlxtend` library to transform the data.

3. **Frequent Itemsets Mining:**
   - Apply the Apriori algorithm to discover frequent itemsets (sets of products purchased together).
   - Set the minimum support threshold to identify itemsets that occur frequently in the dataset.

4. **Association Rules Generation:**
   - Generate association rules using the frequent itemsets.
   - Calculate key metrics such as **support**, **confidence**, and **lift** to evaluate the strength of the relationships between items.

5. **Analysis and Interpretation:**
   - Interpret the results to understand customer purchasing behavior.
   - Provide actionable insights for businesses, such as complementary product recommendations, targeted marketing strategies, and seasonal trend analysis.

## Files

- `Online retail.xlsx`: The dataset used in the analysis (Excel format).
- `association_rule_mining.py`: Python script containing the analysis code.

## Installation

To run this project, you'll need to have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `mlxtend`

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn mlxtend
