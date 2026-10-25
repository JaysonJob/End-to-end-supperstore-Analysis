# End-to-end-supperstore-Analysis
    Python analysis of Super Store retail data to identify profit drivers and strategic insights.
##  Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the classic Super Store retail dataset.The goal is to identify weak areas,uncover hidden opportunities and provide actionable marketing and operational strategies to boost business profitability.

**Target Audience:** The analysis is written in layman's terms,tailored for business owners (assumed to be a small family business) who need clear,data-driven recommendations without needing to understand complex statistics.

##  Tools & Technologies
*   **Language:** Python
*   **Libraries:** Pandas (Data Manipulation),Matplotlib & Seaborn (Data Visualization)
*   **Environment:** Jupyter Notebook

## Business Questions Answered
1. Which Category is Best Selling and Most Profitable?
2. What are the Best Selling and Most Profitable Sub-Categories?
3. Which is the Top Selling Sub-Category by Volume?
4. Which Customer Segment is Most Profitable?
5. Which is the Preferred Ship Mode?
6. Which Region is the Most Profitable?
7. Which City has the Highest Number of Sales?

##  Data Cleaning Process
Before diving into the analysis,the dataset was scrubbed:
*   Checked and confirmed there were no missing (Null) values.
*   Identified and dropped **17 duplicate rows**.
*   Created a new calculated field for **`Profit Margin %`** using the formula:`(Profit / Sales) * 100`.

##  Key Findings
*   **Top Categories:** Technology is both the best-selling and most profitable category.Office Supplies lead in quantity sold (due to lower prices)while Furniture has high sales but very low profitability.
*   **Product Winners & Losers:** Phones and Chairs are the top-selling sub-categories.Copiers generate the highest profit.Conversely,Tables and Bookcases consistently result in heavy losses.
*   **Customer Segments:** The **Consumer** segment is by far the most profitable (followed by Corporate) making up the vast majority of the customer base.
*   **Shipping & Geography:** **Standard Class** is the overwhelming preference for shipping. The **East and West** regions are the most profitable and there is a massive sales disparity between the top 10 cities (e.g.,New York City) and the bottom 10 cities.

##  Strategic Recommendations
Based on the data, the following business strategies are recommended:
1.  **Product Bundling:** Bundle high-profit products (Phones,Chairs,Copiers) with loss-making products (Tables, Bookcases) to offset losses.
2.  **Catalogue Optimization:** Consider dropping heavily loss-making products from the catalogue or negotiating lower prices from suppliers for items like Tables and Bookcases.
3.  **Targeted Marketing:** Focus marketing budgets on the East and West regions,specifically targeting the top 10 cities. 
4.  **B2B & Home Office Packages:** Create curated "Home Office" bundles for busy professionals who don't want to shop for individual items.
5.  **Customer Retention:** Since Consumer and Corporate segments drive >70% of the business,introduce special promotions to retain them and send targeted promotional emails.

The dataset is public on kaggle = https://www.kaggle.com/datasets/akashkothare/tsf-datasets
lets connect:jaysonjobkibet@gmail.com
