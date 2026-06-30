# Supermarket Sales Analysis

## Project Overview
Exploratory data analysis of 1,000 supermarket transactions across three major US cities — Chicago, New York, and Los Angeles — to identify revenue trends, customer behavior patterns, and product performance insights.

## Dataset
- **Source:** Kaggle - Supermarket Sales Dataset
- **Size:** 1,000 transactions, 12 variables
- **Key columns:** city, branch, customer_type, product_category, total_price, reward_points

## Tools
- Python 3
- pandas
- Numpy
- matplotlib

## Business Questions
1. Which city generates the most revenue?
2. Which product category generates the most revenue?
3. Do Members spend more than Normal customers?
4. Which branch has the best overall performance?
5. Which customer type spends more per product category?

## Key Findings
- Chicago leads in total revenue ($42,584), followed by New York ($40,226) and Los Angeles ($35,772).
- Personal Care and Fruits are the top revenue-generating categories, with all categories performing within a similar range (~$6,000 difference).
- Members generate slightly more revenue than Normal customers (53% vs 47%), suggesting an opportunity to expand the loyalty program.
- Branch A serves two cities (Chicago and New York), while Branch B serves only Los Angeles. When comparing average revenue per transaction, Branch A ($122.87) modestly outperforms Branch B ($109.73) — indicating Branch B's lower total reflects market size, not underperformance.
- Personal Care shows the largest spending gap between Members and Normal customers (~$3,700), suggesting targeted promotions could drive higher revenue and increase Member conversion.
