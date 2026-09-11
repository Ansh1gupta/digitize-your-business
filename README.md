# digitize-your-business
Data Analyst Assessment – Brazilian E-Commerce Analysis
# Digitize Your Business – Data Analyst Assessment

## Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset by Olist to identify business opportunities and performance gaps in an e-commerce marketplace.

### Business Problem

How can an e-commerce company improve sales performance and customer satisfaction by identifying high-performing product categories, delivery problems, geographic concentration, and customer trends?

## Dataset

**Dataset:** Brazilian E-Commerce Public Dataset by Olist

**Source:** Kaggle  
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains approximately 100,000 orders from the Brazilian e-commerce marketplace Olist between 2016 and 2018. It includes information about orders, customers, products, sellers, payments, reviews, and delivery.

## Methodology

The analysis was performed using Python, Pandas, NumPy, and Google Colab.

The main steps included:

1. Data cleaning and validation
2. Handling missing values
3. Removing duplicate records
4. Converting date fields to appropriate formats
5. Joining related datasets using order and product identifiers
6. Aggregating order items, payments, and reviews at order level
7. Creating calculated fields such as delivery days and delivery delay
8. Categorizing delivery performance
9. Exploratory data analysis
10. Creating business insights and recommendations
11. Building an interactive dashboard using Looker Studio

## Key Findings

### 1. Product Category Performance

The top 5 product categories account for approximately 39.74% of product sales value, showing that a relatively small group of categories contributes a substantial share of sales.

### 2. Delivery and Customer Satisfaction

Late deliveries have a strong association with lower customer review scores.

- Late delivery: approximately 2.57/5 average review score
- On-time delivery: approximately 4.29/5 average review score
- Late deliveries represented approximately 8.11% of delivered orders

### 3. Geographic Concentration

São Paulo (SP) accounts for approximately 42% of orders. São Paulo, Rio de Janeiro, and Minas Gerais together account for approximately 66.5% of orders.

### 4. Sales Growth

Product sales value increased substantially from 2017 into 2018, with monthly sales reaching approximately R$1 million during several peak months.

### 5. High-Performing Categories

Health & Beauty and Watches & Gifts are among the strongest categories, generating approximately R$1.26 million and R$1.21 million in product sales value respectively.

## Recommendations

1. **Improve delivery reliability**
   - Identify sellers, regions, and categories associated with frequent delays.
   - Monitor late-delivery percentage and customer review scores.

2. **Prioritize high-performing categories**
   - Focus inventory and marketing efforts on strong categories such as Health & Beauty and Watches & Gifts.

3. **Optimize regional operations**
   - Use the concentration of orders in SP, RJ, and MG to improve logistics planning and regional marketing.

## Dashboard

An interactive Looker Studio dashboard was created to monitor:

- Total Orders
- Product Sales Value
- Average Order Value
- Average Review Score
- Late Delivery %
- Monthly sales trends
- Sales by product category
- Orders by customer state
- Customer ratings by delivery status
- Interactive filters for state, category, and delivery status

**Looker Studio Dashboard:**  
https://datastudio.google.com/reporting/d52a8ab3-e977-4996-a1a1-30d30e268990

## Google Drive

The complete Google Sheet, Python notebook, and supporting project files are available in the Google Drive folder.

**Google Drive Folder:**
https://drive.google.com/drive/folders/1UTNn4Y4UxgOY2Ty9PkkQMhXS_xbo9VYI?usp=sharing 


## Files

- `Olist_Data_Analysis.ipynb` – Python data processing and analysis notebook
- `Presentation.pdf` – Project presentation
- `Presentation.pptx` – Editable presentation
- `README.md` – Project documentation

## Limitations

- The dataset covers 2016–2018 and may not represent current e-commerce behavior.
- The dataset does not contain costs, profit margins, marketing spend, or customer acquisition costs.
- Missing delivery dates and review scores limit some analyses.
- The analysis identifies associations between variables and does not establish causation.

## AI Tools Used

AI tools were used as supporting tools for analysis planning, problem solving, and presentation creation.

- **ChatGPT:** analysis support, Python/Pandas logic, interpretation, and recommendations.
- **Gamma AI:** presentation structure and visual presentation.
- **Google Colab/Python:** data processing and analysis.
- **Looker Studio:** interactive dashboard creation.

AI-generated outputs were checked against the processed dataset and analysis results before being included in the final project.
