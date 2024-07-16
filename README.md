# 5G-Telecom-Analysis

Input contains all the  information regarding the columns described in the CSV files. 
1. dim_cities
2. dim_date
3. dim_plan
4. fact_atliqo_metrics
5. fact_market_share
6. fact_plan_revenue



Column Description for dim_cities:
1. city_code: This column represents the unique code given for each city.
2. city_name: This column represents the name of the city corresponding to the city code.



Column Description for dim_date:
1. date: This column represents the starting date of each month. 
2. month_name: This column represents the month names in abbreviated form(Example: Jan, Feb, Mar, etc). We have months starting from January to September except for May.
3. before/after_5g: This column represents the unique category based on the month. We have 2 categories, Before 5G and After 5G. January to April comes represents the period before 5G implementation and June to September represents periods after 5G implementation.
4. time_period: This column represents the unique sequence number ranging from 1 to 4. These time Periods are used to make respective months comparisons before and after 5G implementation (Example: Jan vs Jun, Feb vs Jul, Mar vs Aug and Apr vs Sep)




Column Description for dim_plan:
1. plan: This column represents the various internet plans provided by the Atliqo company to the users. 
2. plan_description: This column represents the brief description about the internet plan.



Column Description for fact_atliqo_metrics:
1. date: This column represents the starting date of each month.
2. city_code: This column represents the unique pincode code given for each city.
3. company: This column represents the company name for which the data is provided. In this dataset it's only Atliqo. 
4. atliqo_revenue_crores: This column represents the revenue that Atliqo got on that particular month in that city_code in crores(unit of currency in India - 1Crore = 10 Million) from the internet users. 
5. arpu: This column represents the average revenue per user. That means on average how much revenue Atliqo generated on single user for a given time period.
6. active_users_lakhs: This column represents the number of active users who are using Atliqo's service on that particular month in that city_code in lakhs(unit of currency in India - 1 Lakh = 100,000).
7. unsubscribed_users_lakhs: This column represents the number of unsubscribed users who unsubscribed from Atliqo on that particular month in that city_code in lakhs(unit of currency in India - 1 Lakh = 100,000). 




Column Description for fact_market_share:
1. date: This column represents the starting date of each month.
2. city_code: This column represents the unique code given for each city.
3. tmv_city_crores: This column represents the total market value of the city in that month in crores(unit of currency in India) from the internet users. 
4. company: This column represents the different competitor names in the telecom industry [Atliqo, Britel, DADAFONE, PIO, Others].
5. ms_pct: This column represents the percentage of market share gained by respective company from the total market value(tmv_city) on that particular month in that city-code. 




Column Description for fact_plan_revenue:
1. date: This column represents the starting date of each month.
2. city_code: This column represents the unique code given for each city.
3. plans: This column represents the various internet plans provided by the Atliqo company to the users.
4. plan_revenue_crores: This column represents the revenue that Atliqo got from that respective plan on that particular month in that city_code in crores (unit of currency in India - 1Crore = 10 Million).

Steps Followed:
1. Data Loading

2. Data Preprocessing & Transformation

3. Data Modelling

4. DAX Queries
      Total Revenue for all periods before 5G implementation
      Total Revenue for all periods after 5G implementation
      ARPU of periods before 5G implementation
      ARPU of periods after 5G implementation
      Total active users for all periods before 5G implementation
      Total active users for all periods after 5G implementation
      Total unsubscribed users for all periods before 5G implementation
      Total unsubscribed users for all periods after 5G implementation
      Total Unsubscribed Users	
      Monthly active users
      Market Share %	MS %
      Revenue Before 5G	
      Revenue After 5G	
      ARPU Before 5G	
      ARPU After 5G	


5. Data Visualzation

6. Report Generation



![Screenshot_16-7-2024_23614_](https://github.com/user-attachments/assets/25ed09b2-7e88-4bf0-8c52-0514f8aa81d2)
![Screenshot_16-7-2024_23634_](https://github.com/user-attachments/assets/30c64b76-50c0-4987-9085-73e66e6dd845)
![Screenshot_16-7-2024_23652_](https://github.com/user-attachments/assets/364029a5-afde-401e-869c-bd8677e7b40c)
![Screenshot_16-7-2024_2375_](https://github.com/user-attachments/assets/45f8ba4e-fa89-4454-9a7e-5801089eeff1)
![Screenshot_16-7-2024_23719_](https://github.com/user-attachments/assets/5718b768-47e3-4b9f-954f-5fa1393a4a03)





