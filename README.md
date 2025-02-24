# elist_analysis
Sales trends analysis for e-commerce company.

Founded in 2018, Elist is an e-commerce company that sells popular electronics products and has since expanded to a global customer base. Like most e-commerce companies, Elist sells products through their online site as well as through their mobile app. They use a variety of marketing channels to reach customers, including Email campaigns, SEO, and affiliate links. Over the last few years, their more popular products have been products from Apple, Samsung, and ThinkPad. 
This data analysis was done in partnership with the head of operations to deliver insights to teams across the company, including finance, sales, product, and marketing. The focus was to help these stakeholders understand Elist’s performance so they can improve their day-to-day processes and help the company deliver top-notch products to customers around the world.

## ERD
<img width="697" alt="Screenshot 2025-02-03 at 12 36 20 PM" src="https://github.com/user-attachments/assets/4e7cdfbe-6919-4c3e-838e-0b31abb9b6bb" />

# Key Business Questions

These main business questions led to a detailed analysis in sales trends, growth rates, product trends, loyalty program, and refund rates. 

* What were the monthly and yearly number of sales throughout 2019 and 2022? What about AOV and total sales in dollars? How did this differ by product and geography?
* Which months and products performed the best / worst? Is there seasonality?
* Should we keep using the loyalty program?
    * What was the monthly number of sales and AOV for people in the loyalty program vs. those not in the loyalty program?
    * How does this trend differ for recent months vs. previous months?
* What are the refund rates for different products?
    * How does it compare between loyal and non-loyal customers?
* How was the growth rate distributed across regions? (i.e. was a dramatic spike observed across all regions, or only some)?
	  * Are the regions with the highest spike the same regions responsible for the highest sales dollars?
  
# Executive Summary

* From 2019 to 2022 the average yearly sale revenue was $7M, the average total orders per year was 27K and the average AOV was $254. 2020 was the strongest year for both total sales (>$10M) and average value of orders($300). 

* From 2020-2022 the overall trend has been a decline in all these metrics, but with average values still higher or equal (AOV =) than those registered in 2019. 

![Screenshot 2025-02-24 at 2 58 57 PM](https://github.com/user-attachments/assets/8bfd1707-65c3-4c27-9bcf-665034f871d3)

  
# Deep-Dive Insights
## Sales Trends

* 2020: Peak Performance. 2020 was the strongest year, with the highest growth.
	* 163% year-over-year surge in total sales revenue.
	* Drivers:
		* 31% increase in Average Order Value (AOV).
		* 101% increase in order volume.
    	* Top-performing month: December. Nearly $1.2 million in sales
* 2021: Shift in Purchasing Behavior. Despite a 15% decline in AOV, order volume reached a record high (up 6%), indicating a shift towards lower-priced items.
* 2021-2022: Declining Trend. A declining trend in sales revenue, AOV, and order volume occurred from 2020 to 2022.
* Average monthly sales have decreased, reaching a low in October 2022.
* A clear seasonal pattern emerges, with sales consistently peaking at the end of the year and reaching their nadir in February across all regions. Despite this seasonality, recent trends raise concerns.

![Screenshot 2025-02-24 at 3 20 17 PM](https://github.com/user-attachments/assets/86f7d712-e6f4-4ec7-9f37-56cb185364d7)

## Monthly analysis and Growth Rates

* March 2020 saw the highest growth in sales (50% MoM, 162% YoY) and order count (46%). Since then, however, key metrics have declined. Average monthly sales have fallen, reaching a low point in October 2022.
* Order count, averaging approximately 2,200 per month, ranged from over 4,000 (December 2020) to just 825 (October 2022).
* AOV, while averaging $253, fluctuated between $216 (October 2022) and $322 (October 2020), with peak growth of 18% in September 2022.
* The most concerning period was September-October 2022, marked by significant contractions in total sales (-55%), AOV (-16%), and order count (-47%).

![Screenshot 2025-02-24 at 3 43 24 PM](https://github.com/user-attachments/assets/1a48ede2-abf8-4b5d-9cbf-9914d62bf4d7)

* Regional contributions to sales remained stable, with North America (NA) consistently generating around 50% and EMEA approximately 30% . The March 2020 growth was primarily driven by EMEA and APAC
  
![Screenshot 2025-02-24 at 3 48 06 PM](https://github.com/user-attachments/assets/4c1b6bbe-9df9-4209-9b9c-a724838572dd)

* Although November and December 2022 suggest a potential recovery, further analysis is warranted to understand the drivers of these declines and ensure a return to growth.

## Product Trends

* Across all regions and the entire four-year period, four products dominated sales: the 27-inch 4K gaming monitor, Apple AirPods Headphones, MacBook Air Laptop, and ThinkPad Laptop.  

* Impact of the COVID-19 pandemic: high demand for remote work solutions and digital entertainment (as seen in the March 2020 peak of 50% sales growth and 46% order growth, with sales concentrated in products like the 27-inch 4K gaming monitor, MacBook Air laptop, Apple AirPods headphones, and ThinkPad laptop). 

![Screenshot 2025-02-24 at 3 58 37 PM](https://github.com/user-attachments/assets/9e0268f8-8017-4519-b8fb-74704fac85ef)


## Loyalty Program

### Loyal customer engagement (Contribution to number of orders):
* Increased from 2019 to mid-2022, reaching 55%.
* Declined by the end of 2022, suggesting a return to non-loyal customer dominance.

### Average Order Value (AOV):
* 2020: Non-loyal customers had a higher AOV.
* 2022: Loyal customers' AOV surpassed non-loyal customers' by 14%.

![Screenshot 2025-02-24 at 4 26 32 PM](https://github.com/user-attachments/assets/82910e19-02ed-4728-8159-bcf67e11b66c)

![Screenshot 2025-02-24 at 4 14 49 PM](https://github.com/user-attachments/assets/bd88a249-28ac-407c-af0b-8d4700f26d36)  

![Screenshot 2025-02-24 at 4 09 14 PM](https://github.com/user-attachments/assets/29cbda41-19c5-4f82-999a-5c3ce78e6b86)
* These shifts, particularly since August 2022, question the loyalty program's effectiveness. A three-month observation period is recommended to validate these trends and determine necessary program adjustments
  
## Refund Rates
Body text
