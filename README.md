# E-Commerce-Product-Delivery-Prediction
🚚 Product Delivery Prediction using Machine Learning
📌 Project Overview
This project aims to predict whether products from an international e-commerce company—primarily dealing in electronics—will reach customers on time. In addition to building a predictive model, the project explores key factors influencing delivery performance and provides insights into customer behavior and logistics efficiency.

📊 Data Overview
The dataset comprises 10,999 records with 12 variables, capturing both customer and product-related details.

Variable	Description
ID	Unique ID assigned to each customer
Warehouse_block	Warehouse location block (A, B, C, D, E)
Mode_of_Shipment	Shipment method (Ship, Flight, Road)
Customer_care_calls	Number of shipment inquiry calls made by the customer
Customer_rating	Rating provided by the customer (1 = Lowest, 5 = Highest)
Cost_of_the_Product	Price of the product in USD
Prior_purchases	Number of previous purchases by the customer
Product_importance	Importance level of the product (Low, Medium, High)
Gender	Gender of the customer (Male, Female)
Discount_offered	Discount percentage on the product
Weight_in_gms	Weight of the product in grams
Reached.on.Time_Y.N	Target variable (0 = On time, 1 = Delayed)

🔍 Key Insights from Analysis
Product Weight & Cost:
Products weighing between 2500–3500 grams and costing under $250 were more likely to be delivered on time.

Shipping Mode & Warehouse Impact:
Most shipments originated from Warehouse F via Ship, indicating its likely proximity to a seaport and better logistical performance.

Customer Behavior:

More customer care calls were linked to delayed deliveries.

Customers with higher prior purchases showed improved on-time delivery, suggesting stronger brand loyalty.

Discount Impact:
Products with discounts above 10% had better delivery performance, while lower or no discounts correlated with delays.

🤖 Model Performance
Several machine learning models were evaluated to predict delivery status:

Model	Accuracy
Decision Tree Classifier	69%
Random Forest Classifier	68%
Logistic Regression	67%
K-Nearest Neighbors	65%

The Decision Tree Classifier emerged as the top performer, offering a good balance between interpretability and predictive power.

📌 Conclusion
This project successfully demonstrates the use of machine learning to predict delivery timeliness and uncovers meaningful business insights. Factors such as product weight, customer loyalty, discount rates, and shipping logistics play a vital role in influencing whether a product arrives on time. These findings can be leveraged to optimize future delivery strategies and improve overall customer satisfaction.
