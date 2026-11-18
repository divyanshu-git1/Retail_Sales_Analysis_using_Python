# Retail Data Analysis | Customer Behavior, Sales & Business Insights

## Project Overview

This project focuses on analyzing retail transaction data to uncover customer purchasing patterns, product category preferences, store performance, return behavior, and revenue opportunities.

The objective is to transform raw retail operational data into actionable business insights that can support merchandising decisions, customer segmentation, marketing campaigns, and regional expansion strategies.

The analysis uses three datasets: Customer, Transactions, and Product Hierarchy.

## Business Objectives

The project aims to answer the following business questions:

1. What are the purchasing patterns of male and female customers across product categories?
2. Which store format performs better in terms of transaction volume and revenue?
3. How widespread are product returns, and what impact might they have on business performance?
4. Which customer age group contributes the most to revenue?
5. Which customers demonstrate high purchase frequency and loyalty?
6. Which city could be investigated for potential store expansion?
7. Which customer segments present opportunities for targeted marketing campaigns?

## Datasets

The analysis uses three datasets from retail operational systems.

| Dataset | Description | Key Fields |
|---|---|---|
| Customer | Customer demographic information | Customer ID, DOB, Gender, City Code, Membership Date |
| Transactions | Purchase and return transaction records | Transaction ID, Customer ID, Date, Amount, Qty, Store Type, Product Sub-Category ID |
| Product Hierarchy | Product classification and taxonomy | Product Sub-Category ID, Sub-Category, Category |

## Data Cleaning & Quality Assessment

Before performing exploratory data analysis, I examined the datasets for duplicates, missing values, inconsistent records, and potential data quality issues.

### Key observations

- Identified 13 duplicate records out of 23,040 records (approximately 0.0564%).
- Investigated negative transaction amounts and identified a potential ambiguity: whether negative values represent legitimate product returns or data-entry errors.
- Identified 2,164 return-related records, representing approximately 9.39% of the transaction records.

### Data Quality Considerations

Negative transaction amounts should not automatically be treated as errors. They need to be validated against return indicators and the business rules of the retail system.

## Exploratory Data Analysis & Key Findings

### 1. Gender-Based Product Category Preferences

Analyzed total spending by gender across six product categories.

| Product Category | Female Spending Share | Male Spending Share |
|---|---:|---:|
| Category 1 | 48.42% | 51.58% |
| Category 2 | 51.51% | 48.49% |
| Category 3 | 46.81% | 53.19% |
| Category 4 | 50.38% | 49.62% |
| Category 5 | 48.12% | 51.88% |
| Category 6 | 49.00% | 51.00% |

**Insights:**
- Male customers contribute a higher spending share in categories 1, 3, 5, and 6.
- Female customers contribute a higher spending share in categories 2 and 4.
- Category 3 has the highest male spending share (53.19%).
- Category 2 has the highest female spending share (51.51%).

**Business Implication:**

The merchandising team can investigate gender-based assortment opportunities, particularly in categories where spending shares differ. Transaction frequency and average spending per customer should also be examined before finalizing inventory decisions.

### 2. Store Format Performance: Volume vs. Value

Compared store formats based on transaction volume and total transaction value.

**Key Finding:**
- E-shop performs better in both transaction volume and transaction value.

**Business Implication:**

The e-shop channel represents an important sales channel. The business can investigate opportunities to improve its digital shopping experience, customer retention, and targeted promotional campaigns.

### 3. Gender-Based Electronics Spending

Analyzed spending contributions in the Electronics category.

**Key Finding:**
- Male customers contribute approximately 53.2% of electronics spending.
- Female customers contribute approximately 46.8%.

**Business Implication:**

The business can explore targeted electronics promotions and product assortment strategies while avoiding assumptions that spending share alone represents customer preference.

### 4. Customer Loyalty Analysis

Investigated customers based on purchase frequency.

**Key Finding:**
- Only 6 customers made more than 10 distinct purchases.

**Business Implication:**

The business can investigate its high-frequency customer segment and explore loyalty programs, repeat-purchase incentives, and retention strategies.

### 5. Age-Based Customer Segmentation

Analyzed customer spending across different age groups to identify valuable customer segments.

**Key Finding:**

 <img width="232" height="177" alt="image" src="https://github.com/user-attachments/assets/5a9e83e2-128a-40e4-8c23-ab285b160c39" />
- The 25–35 age group emerged as an important growth segment.
- Combined spending on Books and Electronics for this age group was ₹1,235,451.

**Business Implication:**

The merchandising and marketing teams can investigate targeted campaigns and product bundles for the 25–35 age group, particularly in Books and Electronics.

### 6. Campaign Window Analysis

Analyzed spending by the 25–35 age group during the first two months of 2014.

**Key Finding:**
- Total spending during the campaign window was ₹1,332,830.005.

**Business Implication:**

This provides a baseline for understanding customer spending during the selected period. Comparing it with previous periods and other customer segments would help determine whether the campaign window generated unusual spending patterns.

### 7. Regional Expansion Opportunity

Investigated store distribution across different city codes.

**Key Finding:**
- City Code 6 has a comparatively lower number of stores.

**Business Implication:**

City Code 6 can be considered for further regional expansion analysis. However, lower store availability alone does not establish market demand. Population, customer density, existing revenue, purchasing power, and competitor presence should be evaluated before recommending a new store location.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Exploratory Data Analysis (EDA)
- Statistical Analysis

## Analytical Skills Demonstrated

- Data cleaning and preprocessing
- Duplicate and return transaction analysis
- Customer segmentation
- Gender-based spending analysis
- Product category performance analysis
- Store format comparison
- Customer loyalty analysis
- Revenue and transaction analysis
- Business insight generation
- Data-driven decision-making

## Conclusion

This project demonstrates how retail operational data can be transformed into meaningful business insights.

The analysis identified differences in category-level spending contributions, the importance of the e-shop channel, a high-frequency customer segment, and potential opportunities in age-based marketing and regional expansion.

The findings provide a foundation for further investigation into customer retention, merchandising optimization, marketing effectiveness, and retail expansion strategies.

## Future Scope

- Perform statistical significance testing to validate gender and category associations.
- Analyze return rates by product category and store format.
- Investigate customer lifetime value (CLV).
- Develop customer segmentation using RFM analysis.
- Evaluate campaign effectiveness using before-and-after comparisons.
- Build an interactive Power BI dashboard for business stakeholders.

---

**Project Focus:** Retail Analytics | Exploratory Data Analysis | Customer Behavior | Business Intelligence


 

  
