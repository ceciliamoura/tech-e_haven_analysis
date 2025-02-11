# elist_analysis
Sales trends analysis for e-commerce company.

Founded in 2018, Elist is an e-commerce company that sells popular electronics products and has since expanded to a global customer base. Like most e-commerce companies, Elist sells products through their online site as well as through their mobile app. They use a variety of marketing channels to reach customers, including Email campaigns, SEO, and affiliate links. Over the last few years, their more popular products have been products from Apple, Samsung, and ThinkPad. 
This data analysis was done in partnership with the head of operations to deliver insights to teams across the company, including finance, sales, product, and marketing. The focus was to help these stakeholders understand Elist’s performance so they can improve their day-to-day processes and help the company deliver top-notch products to customers around the world.
 
# Executive Summary

From 2019 - 2022 while the overall sales trend is upwards, there's noticeable fluctuations in sales. 2020 saw the highest growth, with total sales revenue surging 163% year-over-year, driven by a 31% increase in average order value (AOV) and a 101% jump in order volume. Despite a 15% AOV decline in 2021, order volume still reached a record high (up 6%), suggesting a shift towards lower-priced items. From 2019 to 2022 the average yearly sale revenue was $7M, the average total orders per year was 27K and the average AOV was $254. 2020 was the strongest year for both total sales (>$10M) and average value of orders($300). From 2020-2022 the overall trend has been a decline in all these metrics, but with average values still higher or equal (AOV =) than those registered in 2019. 

## ERD
<img width="697" alt="Screenshot 2025-02-03 at 12 36 20 PM" src="https://github.com/user-attachments/assets/4e7cdfbe-6919-4c3e-838e-0b31abb9b6bb" />

# Deep-Dive Insights
These main business questions led to a detailed analysis, revealing important insights: 
* What were the monthly and yearly number of sales throughout 2019 and 2022? What about AOV and total sales in dollars? How did this differ by product and geography?
* Which months and products performed the best / worst? Is there seasonality?
* Should we keep using the loyalty program?
    * What was the monthly number of sales and AOV for people in the loyalty program vs. those not in the loyalty program?
    * How does this trend differ for recent months vs. previous months?
* What are the refund rates for Apple products?
    * What are the refund rates for each of the Apple products? How does this differ by year?
* How was the growth rate distributed across regions? (i.e. was a dramatic spike observed across all regions, or only some)?
	  * Are the regions with the highest spike the same regions responsible for the highest sales dollars?

## Sales Trends
From 2019 to 2022 the average yearly sale revenue was $7M, the average total orders per year was 27K and the AOV was $254. 2020 was the strongest year for both total sales (>$10M)  and average value of orders($300). From 2020-2022 the overall trend has been a decline in all these metrics, but with average values still higher or equal (AOV =) than those registered in 2019.

A clear seasonal pattern emerges, with sales consistently peaking at the end of the year and reaching their nadir in February across all regions. Despite this seasonality, recent trends raise concerns.

![Screenshot 2025-02-11 at 12 06 44 PM](https://github.com/user-attachments/assets/a4536d00-3119-41ef-80f8-ea9b026939e3)
![Screenshot 2025-02-11 at 12 09 37 PM](https://github.com/user-attachments/assets/45a9b2b0-fa7d-4263-9aaa-7e4eb7e4ead1)


## Growth Rates
December 2020 was the top-performing month, generating nearly $1.2 million in sales, and March 2020 saw the highest growth in sales (50% MoM, 162% YoY) and order count (46%). Since then, however, key metrics have declined. Average monthly sales have fallen, reaching a low point in October 2022. Order count, averaging approximately 2,200 per month, ranged from over 4,000 (December 2020) to just 825 (October 2022). AOV, while averaging $253, fluctuated between $216 (October 2022) and $322 (October 2020), with peak growth of 18% in September 2022. The most concerning period was September-October 2022, marked by significant contractions in total sales (-55%), AOV (-16%), and order count (-47%). 

Although November and December 2022 suggest a potential recovery, further analysis is warranted to understand the drivers of these declines and ensure a return to growth.

![Screenshot 2025-02-11 at 12 39 41 PM](https://github.com/user-attachments/assets/7f349521-a2c2-45b8-9aa3-dfabc9234907)


## Product Trends
Across all regions and the entire four-year period, four products dominated sales: the 27-inch 4K gaming monitor, Apple AirPods Headphones, MacBook Air Laptop, and ThinkPad Laptop. These products collectively represented approximately 95% of total sales. Regional contributions to sales remained stable, with North America (NA) consistently generating around 50% and EMEA approximately 30% .

These findings likely reflect the impact of the COVID-19 pandemic, which initially drove demand for remote work solutions and digital entertainment (as seen in the March 2020 peak of 50% sales growth and 46% order growth, with sales concentrated in products like the 27-inch 4K gaming monitor, MacBook Air laptop, Apple AirPods headphones, and ThinkPad laptop). Although regional sales contributions remained consistent (NA ~50%, EMEA ~30%), the March 2020 growth was primarily driven by EMEA and APAC

## Loyalty Program
Loyal customer engagement, while increasing in order count contribution from 2019 to mid-2022 (reaching 55%), declined by the end of 2022, suggesting a return to non-loyal customer dominance. A similar fluctuation occurred with average order value (AOV). Non-loyal customers had a higher AOV in 2020, but loyal customers surpassed them by 14% in 2022, only to see non-loyal customer AOV rise again recently. These shifts, particularly since August 2022, question the loyalty program's effectiveness. A three-month observation period is recommended to validate these trends and determine necessary program adjustments

![Screenshot 2025-02-11 at 11 45 26 AM](https://github.com/user-attachments/assets/83cdcffd-b662-4ede-9745-6d19a5eefc73)
![Screenshot 2025-02-11 at 11 59 52 AM](https://github.com/user-attachments/assets/a440c5b1-0497-4c77-a322-f3181aac8ae6)

## Refund Rates
Body text
