# Ecommerce-Sales-Dashboard

### Dashboard Link : https://lookerstudio.google.com/s/t1uGUv3UI6A

## Problem Statement

This dashboard helps the ecommerce store to understand their sales better. It helps the store to know detailed information through different visualizations, they get to know total sale across the sates of US, yearly sale and profit, sales in different segment,sales through different category and subcategory.This ecommerce sales dashboard inhibits helps to analyze key performance metrics, identify trends, and make data-driven decisions, thereby limiting our competitiveness and growth potential in the marketplace.
 




### Steps followed 

- Step 1 : Import data into google sheet then import the google sheet in looker studio.
- Step 2 :Scorecard visuals(KPI) were added to the canvas, to show different KPI such as total customer, total sale, profit, total quantity, average order value.To calculate average order value and total customer calculated field were used.
        

![Screenshot 2024-06-30 120251](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/5aa7590f-1ecd-49cc-9f24-ba9df6a05519)

  Following expressions were written to calculate total customer and average order value ,
        
        Total Customer = COUNT_DISTINCT(Customer ID)
        Average Order Value = SUM(Sales)/SUM(Quantity)
- Step 3 :  Controls were added for four fields named "year", "region", "Segment" & "category" to filter out data through different Controls.
  
![Screenshot 2024-06-30 120238](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/27a3127a-11de-442b-9834-fc18ca2eaa11)
- Step 4 : Add table with heatmap,add city in dimension and add sale and profit in metric field then add filter of top 10 and sort it in descending order to show top 10 city name by sale.
  
![Screenshot 2024-06-30 120053](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/d303030f-94d3-4818-bb74-a6d3f1e0588e)

- Step 5 : Add pie chart to show sales in different segment and sales through different subcategory.
  
![Screenshot 2024-06-30 154922](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/6780fef8-432a-433a-a5a9-2a284808106f)

- Step 6 : Add bubble map chart to show sales in different states of US.
  
![Screenshot 2024-06-30 120201](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/c8481e99-4f3c-4316-a0d8-6075d94dc584)

- Step 7 : Add stacked bar chart,then add Year in dimension field before that to show yearly data use calculated field to find years and add sale in metric field to show yearly sale and profit.
  
![Screenshot 2024-06-30 120212](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/ff216319-08c5-4167-9cf8-5aa2af911c31)
           
- Step 8 : Add bar chart,then add shipmode in dimension field and sale in metric field to show sales by shipmode.
  
![Screenshot 2024-06-30 120222](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/749e1607-c1b5-4252-a5db-5c879a7adb3b)
 
 - Step 9 : The report was then published.
 
 # Report Snapshot (Looker Studio)

 
![Screenshot 2024-06-30 164010](https://github.com/Smitamane25/Employee-Details-Dashboard/assets/171058471/16fab04e-4f32-447a-bc69-6df5f3f64a9d)

# Insights

A single page report was created on looker studio & it was then shared with people.

Following inferences can be drawn from the dashboard;

### [1] Total 

      a) Total Customer = 793
      b) Total Sale = 22,97,201
      c) Profit = 2,86,397
      d) Quantity = 37,873
      e) Average Order Sale = 61

  ### [2] Sales by segment
  
      a) Consumer = 50.6%
      b) Corporate = 30.7%
      c) Home Office = 18.7%
The highest sale in consumer segment.

 ### [3] Sales through subcategory
 
 The highest sale through phone and chairs


 ### [4] Location

      a) California
      b) New York
      c) Texas
Above three states of US have maximum sale .

### [5] Yearly sale and profit
  
Yearly sale and profit is increasing.

### [6] Sales by shipmode
  
 Sales through standard class shipmode is highest.
     

  


