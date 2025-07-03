# DSA-Capstone-Case-Study-1-Amazon-Product-Review-Analysis.
## The dataset contains information scraped from Amazon product pages. 

### Dataset Description
‎Each row in the dataset represents a unique Amazon product and includes:

‎- **Product details**: Name, category, price, discount, rating.

‎- **Customer engagement**: User reviews, titles, and content.


### 🔧 Tools Used
‎- Microsoft Excel

‎- Pivot Tables

‎- Pivot Charts
‎
## 📊 Pivot Table Insights
‎
‎The pivot tables and charts were used to explore:

‎1. The average discount percentage by product category

‎2. Number of products are listed under each category

‎3. What is the total number of reviews per category

‎4. Products have the highest average ratings

‎5. The average actual price vs the discounted price by category

‎6. products have the highest number of reviews

‎7. Number of products with discount of 50% or more

‎8. the distribution of product ratings (e.g., how many products are rated 3.0,
‎4.0, etc.)

‎9. The total potential revenue (actual_price × rating_count) by category

‎10. the number of unique products per price range bucket (e.g., <₹200,
‎₹200–₹500, >₹500).

‎11. How does the rating relate to the level of discount?

‎12. products with fewer than 1,000 reviews

‎13. Categories that has products with the highest discounts

‎14. The top 5 products in terms of rating and number of reviews combined.

## Analysis
## Data cleaning and preparation
The data was cleaned by removing the duplicates and also the null values and some others columns were add like **potential revenue = Actual price * Rating count** and **Price Bucket** using the **IF** function:  **=IF(D2 < 200, "<₹200", IF(D2 <= 500, "₹200–₹500", ">₹500"))**

![KMS 1](https://github.com/user-attachments/assets/80b77e21-5653-4fa8-8976-2752e3bbbc7c)
![KSM 2](https://github.com/user-attachments/assets/bbc5f2cb-56d5-44fb-b78a-a0b3166941ef)
![KSM 3](https://github.com/user-attachments/assets/b1e0d998-dd3a-46fa-bc91-bc0240ed8542)
![KMS 4](https://github.com/user-attachments/assets/11313755-c95e-4329-88d6-402d1c202e75)

### Key Findings
‎
‎- Products in the **Electronics** category had the highest discount price.

‎- **Discounted items** generally had **higher potential revenue**, possibly due to increased purchases.

### File Contents
‎- `GODWIN OYEWALE DSA EXCEL ASSIGNMENT.xlsx` – Excel workbook with pivot tables and charts.


‎
‎
