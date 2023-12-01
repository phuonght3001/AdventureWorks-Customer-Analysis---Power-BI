# AdventureWorks Customer Analysis - Power BI
Customer Segmentation and Profiling
## 1. Introduction
### Business context:
  Adventure Works Cycles, a large, multinational manufacturing company,  produces and distributes metal and composite bicycles to North American, European,  and Asian commercial markets. While its base operation is located in Bothell,   Washington, and employs 500 people, several regional sales teams are located throughout the company’s market region. In 2000, Adventure Works Cycles bought a   small manufacturing plant, Wide World Importers, which is located in Mexico City,  Mexico. Wide World Importers manufactures several critical subcomponents for the  Adventure Works Cycles product line. These subcomponents are shipped to the Bothell  location for final product assembly. In 2001, Wide World Importers became the sole  manufacturer and distributor of the touring bicycle product group. 
  After a successful fiscal year, Adventure Works Cycles is looking to broaden its  market share by focusing its sales efforts on the company’s best customers. The sales team needs to to know customer segmentation and profiling whom they should focus efforts for building longterm-relationship.
## 2. Visualization and Insights
### 2.1 Overview
![Overview](https://github.com/phuonght3001/AdventureWorks-Customer-Analysis---Power-BI/assets/150796721/de8a23f2-a3b5-4f05-93df-ec3f09402288)
In general, in the period from Q2 2011 to Q2 2014, the company's revenue, profit and profit margin tended to increase.
- Revenue: increased from $1M to $12.9M (as of Q1 2014). But Q2 2014 dropped to $7.2M. The reason may be due to the number of customers decreased from 5901 to 5111 => Need to find out the reason why the number of customers decreased.
- Profit: increased from $187,486.92 to $1,579,268.94, approximately 8.4 times.
- Profit margin: increased from 19.47% to 21.86%. However, profit margin in the second quarter of 2012 decreased sharply (to -1.18%), because profit decreased to -$106,123.48.

The number of customers tends to increase sharply from 184 (Q2 2011) to 5901 (Q1 2014). Then decreased to 5111 (Q2 2014).

From 2011 to 2014, the highest number of orders was 14,182 in 2013. The reason may be due to the company has effective marketing and gratitude programs for each customer group or because the product models are suitable for large number of customer tastes. Therefore, the profit per customer in 2013 was also the largest (36.91%).

The top 5 customers with the highest revenue spend approximately $13.3K.
### 2.2 Customer Profiling
![CP](https://github.com/phuonght3001/AdventureWorks-Customer-Analysis---Power-BI/assets/150796721/0315f4ce-4609-47be-aa21-3a0137359a71)
The customer with the most spending is Hannah H Clark with a total of 5 orders worth approximately $13.3K.C

Customer Profiling is divided according to the following characteristics:
- Marital Status: married customers have a larger number (54.82%) than single customers (45.18%).
- Education: Bachelors customer group accounts for the largest proportion (28.9%) and Partial High School customer group accounts for the lowest proportion (8.64%).
- Gender: The number of male customers (54.45%) is larger than the number of female customers (45.55%).
- Income level: the group of customers with middle income level (Yearly Income from $25,001 to $100,000) accounts for the largest proportion (75.58%). The customer group with high income level (Yearly Income > $100,000) accounts for the lowest percentage (8.6%)
- Age: the group of customers aged 50-60 accounts for the largest number (3380 people). Therefore, the revenue and profit coming from this group of customers is the highest.
- Occupation: customers belonging to the professional occupation group account for the largest number and customers belonging to the manual occupation group account for the lowest number in all 4 years from 2011 to 2014
- Location: the country with the largest number of customers is Australia (3625).
### 2.3 Customer Behavior
To understand what product models customers tend to buy or within what price range, so that the company can make appropriate policies for each customer group, it is necessary to analyze customer behavior:

![CB](https://github.com/phuonght3001/AdventureWorks-Customer-Analysis---Power-BI/assets/150796721/60e0d2a5-8881-4169-abbd-172e10dd6911)
Most purchased product: Mountain-200 Black,38.
Country with the highest number of purchases: Southwest
In general, each country has the most popular and purchased products:
- Southwest, Canada, Central, Southeast, United Kingdom, France: AWC is the most purchased.
- Northwest, Australia, Germany: Water Bottle - 30oz is the most purchased.
- Northeast: Long-Sleeve Logo Jersey,L is the most purchased.

Top 5 colors of products with the highest revenue: Black, Red, Silver, Yellow, Blue.

Top 4 most purchased products according to each price level:
- Price $4.99: Water Bottle - 30oz
- Price $8.99: AWC Logo Cap
- Price $34.99: Sport-100 Helmet, Blue
- Price $49.99: Long-Sleeve Logo Jersey, L

Revenue and profit of Product line by Class:
- Product line "Mountain" has the largest revenue and profit in High Class.
- Product line "Road" has the highest revenue in Medium and Low Class.

Profit and Average of Discount by Subcategory. There are 5 Subcategories and each Subcategory has a different average of unit price discount: Touring Bikes has the largest average of unit price discount (1.86%) and Road Frames the lowest (0%).

In general, there are several reasons that customers decide to purchase such as price, promotion, manufacturer, review and television advertisement. But the number of customer orders based on the product's price is the highest (17,473 orders), resulting in the largest profit from this customer group ($4,620,137.01).


### 2.4 RFM Analysis
RFM is a technique used to prioritize customers. RFM stands for recency, frequency, and monetary.
- Recency (R) tells us when is the latest purchase date.
- Frequency (F) tells us how frequently do they make purchases.
- Monetary (M) tells us how large their total spending is made. Actually, it is customer lifetime value.

To define RFM score on a scale of 1–5 for each customer in terms of recency, frequency, and monetary value. 1 is the lowest and 5 is the highest.

After calculating R, F, M scores, customers can be divided into 11 groups:
- Champions: Bought recently, buy often and spend the most!
- Loyal Customers: Spend good money often. Responsive to promotions.
- Potential Loyalist: Recent customers, but spent a good amount and bought more than once.
- Recent Customers: Bought most recently, but most often.
- Promising: Recent shoppers, but haven't spent much.
- Customer Needing Attention: Above average recency, frequency and monetary values. May not have bought very recently though.
- About to Sleep: Below average recency, frequency and monetary values. Will lose them if not reactives.
- At Risk: Spent big money and purchased often. But long time ago. Need to bring them back!
- Can't Loose Them: Made biggest purchases and often. But havenn't returned for a long time.
- Hibernating: Last purchase was long back, low spenders and low number of orders.
- Lost: Lowest recency, frequency and monetary scores.
  
![RFM](https://github.com/phuonght3001/AdventureWorks-Customer-Analysis---Power-BI/assets/150796721/9aa23aab-9145-4c92-b6f4-9aba6c5d7097)
The Promising and Recent Customers group accounts for the largest number, approximately 2.84K customers.

The Customer Needing Attention group accounts for the smallest number (224 customers).

The Champions group contributed the largest revenue ($40,732,214.65).

The At Risk group accounted for the largest profit ($2,740,729.69) but had less revenue than the Champions group. Therefore, there needs to have reasonable programs and policies to attract customers in this group back to the company.

## 3. Recommendations
Through the above analysis, there will be 3 groups of solutions for each problem.
### 3.1 Customer Profiling:
- The number of customers with Middle Yearly Income Level accounts for the largest proportion: More product models need to be offered to suit the spending and needs of this group of people.
- It is necessary to have appropriate marketing forms and customer appreciation programs for each age group: research preferences, needs for suitable products, and shopping habits.
### 3.2 Customer Behavior:
- Offer product samples with colors and prices that are most popular with customers.
- Improve methods of approaching customer shopping needs such as promotion, review, manufacturer, and TV ad programs.
### 3.3 For customer segments according to RFM scores:
- Champions: Has loyalty programs with special and highly personalized values. Besides, this group of customers already has high trust and commitment to the brand, the company does not need to attract them with promotional discounts => Instead, increase CLTV (Lifetime Value). of customers) by recommending items with greater value, product combos based on predictions from order history.
- Loyal Customes and Potential Loyalists: Propose incentives tied to spending levels (eg: free gifts for transactions above the brand's average order value or referral programs,...).
- Recent and Promising: Need a thorough and highly personalized care process => build relationships: For example: get feedback on first order experience, give discount vouchers for future purchases .
- Customers Needing Attention and At risk: Need to conduct surveys to find out the reasons why they do not return and provide solutions.
- About to Sleep, Hibernating and Lost: Can send emails, interact via Social Media or call to reconnect with these customers. Businesses can implement programs such as vouchers, exclusive discounts, etc.

