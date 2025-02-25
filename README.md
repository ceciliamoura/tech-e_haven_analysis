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
* How are the sales across regions? (i.e. was a dramatic spike observed across all regions, or only some)?
	  * Are the regions with the highest spike the same regions responsible for the highest sales dollars?
  
# Executive Summary

* From 2019 to 2022 the average yearly sale revenue was $7M, the average total orders per year was 27K and the average AOV was $254. 2020 was the strongest year for both total sales (>$10M) and average value of orders($300) 
* 2020 saw peak performance with 163% YoY revenue growth, driven by a 31% AOV increase and 101% order volume surge.  However, a declining trend followed.
* Regional contributions to sales remained stable, with North America (NA) consistently generating around 50% and EMEA approximately 30%
* Four products (27-inch 4K monitor, AirPods, MacBook Air, ThinkPad) generated 95% of revenue.
* Refund rates, though declining, remain high, especially for laptops (ThinkPad 9%, MacBook Air 7% in 2021) and loyal customers.
* The loyalty program's effectiveness is questionable, with fluctuating engagement and AOV.
* Recommendations include investigating declining sales, optimizing the product portfolio, re-evaluating the loyalty program, and addressing high refund rates. Recent data suggests a potential recovery requiring further analysis.

 
# Deep-Dive Insights
## Sales Trends

* 2020: Peak Performance. 2020 was the strongest year, with the highest growth
	* 163% year-over-year surge in total sales revenue
	* Drivers:
		* 31% increase in Average Order Value (AOV).
		* 101% increase in order volume
    	* Top-performing month: December. Nearly $1.2 million in sales
* 2021: Shift in Purchasing Behavior. Despite a 15% decline in AOV, order volume reached a record high (up 6%), indicating a shift towards lower-priced items.
* 2021-2022: Declining Trend. A declining trend in sales revenue, AOV, and order volume occurred from 2020 to 2022
* Average monthly sales have decreased, reaching a low in October 2022
* A clear seasonal pattern emerges, with sales consistently peaking at the end of the year and reaching their nadir in February across all regions. Despite this seasonality, recent trends raise concerns

![Screenshot 2025-02-25 at 11 04 58 AM](https://github.com/user-attachments/assets/071e187c-d2a6-47e6-8672-3ebf9ccedff4)

## Monthly analysis and Growth Rates

* March 2020 saw the highest growth in sales (50% MoM, 162% YoY) and order count (46%). Since then, however, key metrics have declined. Average monthly sales have fallen, reaching a low point in October 2022
* Order count, averaging approximately 2,200 per month, ranged from over 4,000 (December 2020) to just 825 (October 2022)
* AOV, while averaging $253, fluctuated between $216 (October 2022) and $322 (October 2020), with peak growth of 18% in September 2022
* The most concerning period was September-October 2022, marked by significant contractions in total sales (-55%), AOV (-16%), and order count (-47%)
  
![Screenshot 2025-02-25 at 11 05 34 AM](https://github.com/user-attachments/assets/bc863958-6f7c-4dd0-bd6e-0321c836d092)

* Regional contributions to sales remained stable, with North America (NA) consistently generating around 50% and EMEA approximately 30% . The March 2020 growth was primarily driven by EMEA and APAC
  
![Screenshot 2025-02-25 at 11 06 43 AM](https://github.com/user-attachments/assets/8cc6a59a-658e-4614-b0d4-da9376885dcb)

* Although November and December 2022 suggest a potential recovery, further analysis is warranted to understand the drivers of these declines and ensure a return to growth

## Product Trends

* Across all regions and the entire four-year period, four products dominated sales: the 27-inch 4K gaming monitor, Apple AirPods Headphones, MacBook Air Laptop, and ThinkPad Laptop 

* Impact of the COVID-19 pandemic: high demand for remote work solutions and digital entertainment (as seen in the March 2020 peak of 50% sales growth and 46% order growth, with sales concentrated in products like the 27-inch 4K gaming monitor, MacBook Air laptop, Apple AirPods headphones, and ThinkPad laptop)

![Screenshot 2025-02-25 at 11 18 09 AM](https://github.com/user-attachments/assets/9de9d17f-2bc1-4024-ac31-be9f5c2928d7)

![Screenshot 2025-02-25 at 11 08 04 AM](https://github.com/user-attachments/assets/8289280b-e16c-408a-a3c8-ed147afe2ab2)

 * The Samsung Webcam has guaranteed a fair share of the orders, reaching 11% of participation 3 years after its introduction
 * Samsung Charging Cable Pack is the 3rd most ordered item but accounts for only 1.5% of total Revenue
 * While laptops constitute only about 4% of total orders, they contribute roughly one-third of total revenue
 * Apple iPhone and Bose Soundsport Headphones sales each represent less than 1% of total orders and revenue
 	* Bose Headphones, in particular, saw an 82% year-over-year decline in order volume in 2022


## Loyalty Program

### Loyal customer engagement:
* Their contribution to number of orders increased from 2019 to mid-2022, reaching 55%
* Declined by the end of 2022, suggesting a return to non-loyal customer dominance

### Average Order Value (AOV):
* 2020: Non-loyal customers had a higher AOV
* 2022: Loyal customers' AOV surpassed non-loyal customers' by 14%

![Screenshot 2025-02-25 at 11 08 45 AM](https://github.com/user-attachments/assets/0941135d-7503-4a9b-aa20-5c72a30746ad)

![Screenshot 2025-02-25 at 11 23 52 AM](https://github.com/user-attachments/assets/d9d1d602-e427-4650-8697-463c99f56928)

![Screenshot 2025-02-25 at 11 33 22 AM](https://github.com/user-attachments/assets/a383ba74-b027-4d81-a078-2ad38d1e1c19)

* These shifts, particularly since August 2022, question the loyalty program's effectiveness. A three-month observation period is recommended to validate these trends and determine necessary program adjustments


## Refund Rates

* At the analysis time there was no refund information for 2022
![Screenshot 2025-02-25 at 11 01 58 AM](https://github.com/user-attachments/assets/8eb72081-c911-41d8-bb1d-8d9ae02f712d)

* Despite a decrease in the Apple iPhone's refund rate from 11% in 2019 to 5% in 2022, this remains a high rate for a product representing less than 1% of total orders and revenue
* The ThinkPad laptop experienced the highest revenue impact from refunds in 2021, with 9% of its total revenue refunded
* The Macbook Air laptop had the second highest impact, with 7% of its total revenue refunded
* Loyal customers were twice as likely to request refunds as non-loyal customers between 2019 and 2022

## Recommendations

### Optimize product portfolio: 
* Focus on 27-inch 4K monitor, AirPods, MacBook Air, ThinkPad and Samsung Charging Cable Pack, which constitute 95% of revenue and number of orders
* Introducing similar products within the same class could strengthen E's competitive position, leading to improved sales and greater market penetration
* Evaluate the continued viability of low-performing products (Apple iPhone, Bose Soundsport Headphones) given their <1% contribution to orders and revenue. Investigate the high order volume for the Samsung Webcam (11% of orders)

### Monitor seasonality: 
* Recognize the consistent end-of-year sales peak and the February sales nadir. Plan inventory, marketing campaigns, and staffing accordingly.

### Address high refund rates: 
* Investigate the high refund rates for ThinkPad (9%) and MacBook Air (7%) laptops (2021), and the higher refund rate among loyal customers.
 	* Implement quality control measures, improve product descriptions, or enhance customer support. 
* Analyze the specific issues faced by loyal customers that might be driving higher refunds. 
* Investigate the Apple iPhone's refund rate, even though its sales volume is low, as it still represents a potential issue.


### Analyze regional performance: 
* While regional contributions (NA ~50%, EMEA ~30%) have been relatively stable, I suggest a group talk between sales, marketing, and operations teams to gather insights into any activities or events that might have contributed to the drivers behind the March 2020 growth in EMEA and APAC. 
	* Explore opportunities to replicate this success. 



