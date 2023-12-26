# Capstone-2-Walmart-Analysis

## **Introduction**
Walmart stands as a global retail giant, renowned for its expansive presence and significant impact on the retail industry worldwide. Founded in 1962 by Sam Walton, Walmart began as a single discount store in Rogers, Arkansas. Over the years, it has evolved into a colossal conglomerate, dominating the retail landscape with its diverse range of products, including groceries, apparel, electronics, and more.

With its headquarters in Bentonville, Arkansas, Walmart operates a vast network of hypermarkets, department stores, and grocery stores across various countries, serving millions of customers daily. Its commitment to offering affordable prices and a wide assortment of goods has solidified its position as a household name.

Walmart's success extends beyond its physical stores. The company has embraced e-commerce and technological innovations, enhancing its online presence and services. Through strategic acquisitions and partnerships, it has expanded its digital footprint, providing customers with convenient online shopping experiences through its website and mobile applications.

Moreover, Walmart has continually emphasized sustainability initiatives, aiming to reduce its environmental impact and promote social responsibility. Its initiatives include renewable energy investments, waste reduction programs, and efforts to improve supply chain sustainability.

As a retail powerhouse, Walmart's influence spans not only in sales but also in shaping industry trends and standards. Its strategies, innovations, and socio-economic impact make Walmart a significant player in the global retail sphere.

### **Business Problem Statements**
At present, Walmart is facing several intricate business challenges that necessitate the expertise of a proficient data analyst capable of conducting comprehensive analyses across multiple crucial domains. Specifically, the analyst is tasked with delving into the intricacies of:
1. **Customer Segment Analysis:** 
    - Understanding the diverse customer segments, discerning their distinct preferences and behaviors to refine targeted marketing strategies and foster personalized shopping experiences.
2. **Product Sales Evaluation:**
    - Investigating and interpreting sales patterns across various product categories, identifying underperforming sectors, and formulating strategies to rejuvenate growth trajectories.
3. **Platform/Marketplace Assessment:**
    - Assessing the intricacies of Walmart's online platform to enhance its competitiveness in the dynamic e-commerce sphere, ensuring seamless navigation, and optimizing user experiences for heightened customer engagement.
4. **Promotion Type Optimization:**
    - Strategizing and fine-tuning diverse promotional approaches by meticulously analyzing their effectiveness, experimenting with innovative campaigns, and leveraging customer feedback to enhance engagement and drive sales.
5. **Business Performance Review:** 
    - Conducting a holistic review of Walmart's overall business performance, scrutinizing operational efficiency, cost management, and financial metrics to unearth areas for enhancement and innovation, ensuring sustained growth and market resilience.

In summary, the data analyst's role extends across these pivotal realms, demanding meticulous scrutiny, analytical acumen, and innovative thinking to drive Walmart's strategic evolution and fortify its competitive edge in the dynamic retail landscape.

### **Project Goals**
The overarching goals of this project are centered on augmenting Walmart's profitability through a detailed analysis across several key domains

## **Dataset**
**People**
|Column Name (People)| Description|
|----------|------------|
|ID | Customer's unique identifier|
|Year_Birth | Customer's birth year|
|Education | Customer Education Level|
|Marital_Status | Customer's marital status|
|Income | Customer's yearly household income|
|Kidhome | Number of children in customer's household|
|Teenhome | Number of teenagers in customer's household|
|Dt_Customer | Date of customer's enrollment with the company|
|Recency | Number of days since customer's last purchase|
|Complain | 1 if the customer complained in the last 2 years, 0 otherwise|

**Products**
|Column Name (Product)| Description|
|----------|------------|
|MntWines | Amount spent on wine in last 2 years|
|MntFruits | Amount spent on fruits in last 2 years|
|MntMeatProducts | Amount spent on meat in last 2 years|
|MntFishProducts | Amount spent on fish in last 2 years|
|MntSweetProducts | Amount spent on sweets in last 2 years|
|MntGoldProds | Amount spent on gold in last 2 years| 

**Promotion**
|Column Name (Promotion)| Description|
|----------|------------|
|NumDealsPurchases | Number of purchases made with a discount|
|AcceptedCmp1 | 1 if the customer accepted the offer in the 1st campaign, 0 otherwise|
|AcceptedCmp2 | 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise|
|AcceptedCmp3 | 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise|
|AcceptedCmp4 | 1 if the customer accepted the offer in the 4th campaign, 0 otherwise|
|AcceptedCmp5 | 1 if the customer accepted the offer in the 5th campaign, 0 otherwise|
|Response | 1 if the customer accepted the offer in the last campaign, 0 otherwise|

**Place**
|Column Name (Place)| Description|
|----------|------------|
|NumWebPurchases | Number of purchases made through the company’s website|
|NumCatalogPurchases | Number of purchases made using a catalog|
|NumStorePurchases | Number of purchases made directly in stores|
|NumWebVisitsMonth | Number of visits to the company’s website in the last month|

## **Dashboard**
Tableau: https://public.tableau.com/app/profile/sulthan.dhiaulhaq/viz/Walmart-Dashboard/CustomerSegment?publish=yes

## **Conclusions**
1. **Customer Segment:**
    - **Generation:**
        - The largest total customer currently is Gen X.
        - The generation that shops most often and buys the most products is the boomers generation.
        - The generation that most often receives campaigns is the millennial generation.
        - In general, the distribution of generations at Walmart is good because as a percentage, all of them make frequent purchases and buy a lot of products
    - **Marital Status**:
        - Currently, most Walmart customers fall into the married category.
        - But all marital status categories do not differ significantly in terms of frequent shopping and buying a lot of products, so there is no need to segment customers based on marital status.
    - **Family Member**:
        - Walmart customers mostly have 2 and 3 family members.
        - However, the people who buy the product most often and the most are customers who live alone.
    - **Social Class**:
        - Walmart customers on average have Middle Class and Lower Middle Class social class status.
        - However, the customers who buy products often and a lot are only middle class customers.
    - **Education Level**:
        - The education level of most Walmart customers is graduation.
        - However, education level does not influence frequent purchases and the number of product purchases
2. **Product Sales**
    - The best-selling product is wines, while the product least frequently purchased is fruits
    - A fairly strong correlation occurs between:
        - fruits and fish product
        - meat and fish product
        - sweet and fish product
3. **Platform/Marketplace**
    - Customers most often shop directly from stores
    - The website is still quite good with a total of 8.5k customers
    - Meanwhile, there are quite a few people interested in catalogs
4. **Promotion Type**
    - Campaign no. 3 and no.4 have the most total sales compared to the others. This means that Walmart customers prefer campaign types such as campaigns 3 and 4
    - And vice versa, the lowest campaign was in the second campaign, so it can be said that Walmart customers are not suitable to be given campaign method no. 2.
5. **Business Performance**
    - It can be seen that new customers fluctuate every month, but this should not be a problem because it is still within the normal range.
    - Apart from that, it can also be seen that the complaint rate is very low, namely less than 1%
    - Meanwhile, the churn rate can also be said to be low because it is less than 10%

## **Recommendations**
1. Currently, the people who buy the most products are the boomers generation, even though the majority of Walmart customers are the Gen X generation. Therefore, it would be better if the GenX generation could be paid more attention to.
2. Currently, the millennial generation is the generation that receives the most campaigns. This is a good thing because the millennial generation is Walmart's future customers. Therefore, media campaign no. 3 is the most suitable because it is more in line with the interests of the millennial generation.
3. Currently, the people who buy the most products and buy the most products are people who live alone. Even though the majority of Walmart customers have 2 to 3 family members. So it would be better if we added a new product segment that focuses on household needs.
4. The majority of Walmart customers are middle class and lower middle class. However, those who buy products often and a lot are only middle class customers. Therefore, it would be better if there was a new product segment with a slightly cheaper price range to attract the attention of lower middle class customers.
5. The best-selling product liked by Walmart customers is wine, therefore we can focus on adding to the types of wine menu that we already have.
6. There are several products that have quite a high correlation, such as fruits and fish products, meat and fish products, and sweet and fish products. We can implement a bundling system for these products so that it makes it easier for customers to buy the products they want.
7. The main platform for sales at Walmart is to shop directly at the store. therefore opening a new shop outlet in a strategic location is a good idea.
8. Purchasing via the website is quite good, but it feels like it's still not optimal. It would be better to optimize the website so that it can attract more customers online.
9. Don't ever do campaign method no. 2 again because it has a bad impression on Walmart customers. it's better to use campaign method no. 3 or 4 because it is liked by many Walmart customers.
10. The customer churn rate is good because it is less than 10%, but the customer conversion rate each month is still very fluctuating. So it would be better to carry out a campaign that is targeted at finding new customers rather than user retention.
