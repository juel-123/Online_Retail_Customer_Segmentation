# Online_Retail_Customer_Segmentation

Project Summary
The aim of this ML project is to perform segmentation for an online retail business. Customer segmentation involves dividing a customer base into distinct groups on shared characteristics, behaviours,or preferences.By effectively segmenting customers, businesses can gain valuable insights and tailor their marketing strategies to specific customer Groups, leading to improved customer satisfaction and increased profitability.

Dataset : The project utilizes a dataset containing relevant information about the online retail customers. The dataset contains features such as Customer Demographics, Purchase history, frequency of purchases, monetary value of purchases, and other relevant variables that can help segmenting customers effectively.

Primary objective: The primary objective of this is to apply ML techniques to segment the online retail customers in to meaningful groups based on their purchasing behaviour and characteristics. This segmentation will help the business to better understanding it's customer base, identifying the pattern, trends and develop personalized marketing campaigns to target each segment.



Data Description
Attribute information:

Invoice : Invoce no ,Nominal , a 6-digit integral number assigned to each transcation. if this code starts with 'c' indicates a cancellation.

StockCode : Product(item) code.Nominal , a 5-digit integral number uniquely assigned to each distinct product.

Description: Product (item) name.Nominal

Quantity : The quantities of each product per transcation. Numeric.

InvoiceDate : Invoice date and time. Numeric, the day and time when each transcation was generated.

Unit price: Unit price, Product price on unit selling.

Observations:

Datatype of InvoiceDate is object type need to convert into Datetime
If the InvoiceNo starts with C means it's cancellation. We need to drop this entries.


What is RFM?
RFM(Recency, Frequency, Monetary) analysis is widely used Customer segmentation technique in marketing and analytics.It helps businesses understand and categorize their customers based on three key factors.

Recency: How recently they made purchase.
Frequency: How frequently they make Purchase.
Monetary : How much they spend.
RMF analysis enables businesses to identify and target different customer segment with customized marketing approach.

Why it is Needed?
RFM analysis is marketing framework that is used to understand and analyze customer behaivour based on the above three factors Recency, Frequency and Monetary.

The RFM analysis will help the business to segement their customer base into different homogeneous groups so they can engage with each group with different market strategies.




Conclusion
First we did customer segmentation based on RFM analysis.

Platinum customers = 1263 (less recency rate but high frequency and heavy spending)
Gold customers = 1324 (good recency, frequency and monetary)
Silver customers = 981 (high recency ,low frequency and low spending)
Bronze customers = 770 (very high recency but very less frequency and spending amount).
Later we implemented Machine learning algorithms to cluster , as we have seen we got optimal clusters = 2 for all the algorithms.

The RFM analysis emphasizes the importance of personalization in the marketing efforts. By understanding each customer's RFM profile, we can deliver targeted content, product recommendations, and promotions that resonate with their preferences and purchasing history. Personalization enhances customer experience and increases the likelihood of conversion.

The RFM analysis conducted on our online retail business dataset has revealed valuable insights into our customer base and their purchasing behavior. These insights can guide our marketing strategies and customer engagement efforts, ultimately leading to improved customer satisfaction and business growth.

There are null values in CustomerID and Description.
