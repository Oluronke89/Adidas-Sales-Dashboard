# Adidas-Sales-Dashboard


![adidas image](https://github.com/user-attachments/assets/f06507c3-4e2b-4ce7-82c6-efc76c906a3c)

## Introduction
This project is aimed at providing insights into the sales performance of Adidas company, by analysis sales trends, product popularity and regional market performance.

## Problem Statement
1. How does the profit margin impact sales?

2. Which cities are driving the most sales for the business?

3. How does sales performance vary across different geographical regions?

4. Which products are top peforming, which ones are underperforming?

5. Assessing consistency in sales trend over time , any noticeable yearly or monthly trends?

6. Which stores are best and worst performing based on their locations?

7. Which sales method is most effective?

## Skills/ Concepts Demonstrated
  The following Power BI features were incorporated- DAX, Page Navigation, Modelling, Filters, Button.


## Data Sourcing
   The dataset used for this project was obtained from Kaggle named “Adidas Sales Dataset” and was converted from an XLSX file to a CSV file for easier handling.
   
## Data Transformation
   Data was cleaned and transformed using the Power Query Editor of Power BI, this is to ensure data’s quality and reliability. Some of the applied steps included:
   - Checking for duplicate rows in the dataset. Duplicate data can skew analysis results and should be addressed if present. There were no duplicated rows in the dataset.
   - Checking for Null Values: identifying any missing or undefined data in each column Identifying the count of null values in each column helps in deciding how to handle them.
   - Standardizing formats, and resolving any inconsistencies in the dataset. 

## Data Modelling

  ![ER Diagram Adidas](https://github.com/user-attachments/assets/ae72a80b-ea98-4f55-9cad-cbb775e94f5e)

   Power BI automatically connected related tables. The data sales adidas is the fact table of the model. The Adidas sales data was organized into relevant tables, including retailer and calendar table. Relationships were established between 
   these tables. Calendar table was created using the function CALENDARAUTO () to extract different dates such as month, year, month number and quarter.

 ## Data Analysis
     
  ### Home Page:

     
  ![Adidas home page](https://github.com/user-attachments/assets/f5e9b74c-7924-4c59-b35d-c383b80d764c)


 - Total Revenue generated is $899.90M
 - Average Operating Margin is 0.42.
 - Total Unit Sold is 2.48M
 - Total Profit made is $332.13M
    
        
   ### Sales :
    
        
    ![sales](https://github.com/user-attachments/assets/5f3da0a8-310e-41d6-8c9d-8f644a585254)

   ![sales trend](https://github.com/user-attachments/assets/6ff51956-10a7-44ad-9809-4149e0e47ebd)

      -  Men’s Street footwear was the top-selling product at 208,826,244 showing a strong market preference. In contrast, Women’s Athletic Footwear shows a relatively lower performance, recording sales of $106,631,896. This disparity suggests a 
         need for targeted strategies to enhance the appeal of underperforming categories like Women’s Athletic Footwear.
      -  In-store generated the most revenue at 356,643,750(40%), followed by Outlet (295,585,493) 33%, and online at 247,672,882 (28%). In-store sales method is the most effective, generating the highest total sales and operating profit
      -  Retailer “West gear” made the highest purchases, contributing $625,262 to sales, while retailer “Amazon” had the least purchases at $197,990. This aids in optimizing retailer relationships and resource allocation.
      -  High performing cities includes Charleston ( 39,974,797) with the highest sales followed by New York (39,801,235), San Francisco (34,539,220) ,Miami (31,600,863) and Portland  (30,545,652), While Underperforming cities include Omaha 
         (5,929,038), Minneapolis (7,378,668), Desmoines (7,424,011), Milwaukee (7,727,469) and Fargo (7,735,580). Significant variation by city, indicate the need for tailored marketing and sales strategies in different locations, improvement in 
         distribution or potential market development initiatives.
      - West Region recorded the highest sales at $269,943,182 contributing significantly to Adidas overall revenue while Midwest Region has the least sales at $135,800,459. This insights aids in market expansion strategies such as new region 
        penetration and allocation resources to high performing region.
      - High sales were recorded on Thursdays and Fridays . This trends guide proactive strategies to capitalize on these high-demand periods and ensure sufficient resources are allocated to meet customers needs
      - There is a strong correlation between profit and total sales but no correlation between unit sold and unit price. This indicate that operating profit significantly impart sales performance while unit price have no impart on unit sold

    ### Product:


   ![product](https://github.com/user-attachments/assets/62fd9bbf-bf9c-4592-bbc1-66499f6c378c)
     
      -  Men’s Street footwear was the top profitable product at 82,802,261 and Women’s Apparel at 68,650,971. It identifies the products contributing the most to the company’s operating profit and helps assess the effectiveness of pricing 
         strategies, cost management, and product profitability.
      - New York excels in sales in the following products: Men's apparel, Men's athletic footwear and Women's athletic footwear, indicating a strong market for these products. In contrast, Omaha consistently show the lowest sales across various 
        products suggesting limited market demand

 ### Sales Method:


  ![sales method](https://github.com/user-attachments/assets/0ba34290-c552-4eb3-88f1-5c0f63f647ce)

  - In-store sales have both the highest total sales and operating profit, followed by outlet and then online store. In-store is the most efficient in terms of  maximizing total revenue and profit. This helps to evaluate the effectiveness of each 
    channel in reaching target customers, optimizing channel strategies and understanding customer preference.
  - Online sales are the most effective, indicating that although the total sales and operating profit are lower than in-store, the profitability relative to the sales generated is higher.

 ### Trends:

  ![trends](https://github.com/user-attachments/assets/7f4987c4-dec9-4aec-87dd-0972674aabba)

  ![trends analysis](https://github.com/user-attachments/assets/461a7525-a440-4a22-a434-4fb4e9bbe5cf)

  ![trend overview](https://github.com/user-attachments/assets/825603bb-c83f-4577-85a2-20e9f9f42fb6)


- There were consistent increases in sales during months of April and December, traditionally aligned with the holiday season and potential promotional campaigns. Additionally, an increase in sales was observed in April 2020, and growth spikes occurred in January, July and December 2021, indicating shifts in customer behavior during these months
- July 2021 recorded the highest sales at 78,334,681 and December 2020 had the least sales at 8,026,527. July 2021 had the highest profit at 29,137,233.48 and June 2020 had the least operating profit at 2,292,727.41. Highest sales was also observed in the third quarter of the year. Comparing sales by year helps to determine growth rate for each year. This insight helps identify periods of accelerated growth or potential challenges that impact sales performance in specific years, this helps to access the impact of business strategies, market conditions, or external factors on sales over time.
- February, March, October, November and December 2021  recorded a decline in sales MOM and profit MOM.The MOM Sales/ profit metric allows us to assess the growth or decline in profit/sales over time. Positive values suggest growth while negative value suggest decline.
  
 ## Reccomedation

 - Give priority to high performing products and key retail partnerships.
 - Need to launch a targeted strategies to enhance the appeal of underperforming categories like Women’s Athletic Footwear and also investigate underperforming regions and retailers to identify potential for improvement and expansion.
 - Develop digital marketing strategies, improving online user experience, and capitalizing on the growing trend of online shopping.
 
