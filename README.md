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
There are null values in CustomerID and Description.
