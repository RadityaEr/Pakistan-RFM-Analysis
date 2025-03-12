# RFM Analysis of Pakistan's Largest E-Commerce Dataset: Customer Segmentation & Insights Dashboard
![image](https://github.com/user-attachments/assets/bd1472f2-3789-437e-b1c2-c6e84638d955)

This is my personal project to learn how to Analyze a Dataset and build a dashboard in Power BI. The dataset is acquired from [Kaggle](https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset/data).
.It records information on e-commerce transactions from 2016 to 2018 made at multiple marketplaces in Pakistan. It consists of various tables with the following is the one that I will use for the project:

The data preprocessing steps are done in python using [Google Colab](https://colab.research.google.com/drive/13EbynGYYMDx-SxP2p8X4cWS93u99zDcj?authuser=1). Unfortunately, I don't have any Microsoft organization account so I can only export my dashboard into a 
[PDF file](https://drive.google.com/drive/u/1/folders/1hrzrX24RYKQ1vnjDtF6s_hJcneebijny), which is also embedded in this repository

`item_id` → Unique identifier for each item.

`status` → Current status of the order (e.g., shipped, canceled, pending).

`created_at` → Timestamp when the order was placed.

`sku` → Stock Keeping Unit, a unique product identifier.

`price` → Price of a single unit of the item.

`qty_ordered` → Quantity of the item purchased.

`grand_total` → Total amount paid for the order, including discounts and taxes.

`increment_id` → Unique order number assigned by the system.

`category_name_1` → Primary category the item belongs to.

`sales_commission_code` → Code representing sales commission details.

`discount_amount` → Discount applied to the order.

`payment_method` → Method used for payment (e.g., credit card, PayPal, bank transfer).

`MV` → Monetary Value.

`Customer Since` → Date when the customer first registered or made a purchase.

`Customer ID` → Unique identifier for each customer.

# Data Pre-Processing
Before constructing the Power BI dashboard, I first analyzed and cleaned the dataset to ensure data integrity and gain deeper insights—both from a technical and business perspective. 
This involved handling missing values, removing duplicates, and understanding each column’s significance and dropping irrelevant columns. The cleaned dataset is stored as .csv files in the data folder as Clean_Pakistan.csv
- Changing CustomerID into Text and Created_at into Date and Time.
- Organizing Order Status into Groups that means the same thing.
- Duplicate rows across the dataset were identified and removed
- Removing Negative Values in Qty Ordered and Discount, as well as removing Future Dates.

# Customer, Orders, and Payment Preference Dashboard
This Power BI dashboard provides an overview of customer behavior, order trends, and payment preferences in an online marketplace. Key insights include:
![image](https://github.com/user-attachments/assets/3c5355c2-20be-4736-a8be-b460b88d1e63)

Total Sales: 117bn

Total Orders: 408.74K

Average Order Value per User: 1.01M

Unique Customers: 115.33K

Dashboard Features:
 Total Order Over Time – Visualizes order trends from 2016 to 2018.
 
 Order Count by Payment Method – Shows the distribution of transactions across various payment options.
 
 Order Status Breakdown – Displays the proportion of completed, canceled, and unknown orders.
 
 Customer Segmentation – Groups customers based on purchasing behavior (e.g., Champions, Casual Shoppers, Value Seekers).
 
 Most Popular Product Categories – Highlights the top-selling categories.
 
 Total Sales by Customer Segment – Compares revenue contribution from different customer groups.

This dashboard helps businesses understand customer behavior, optimize sales strategies, and improve payment processing efficiency. 🚀
