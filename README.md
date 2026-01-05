**PhonePe Digital Payments Case Study – Transaction & Demographic Analysis**

**Overview:** This case study involves analyzing transaction data from the financial application PhonePe along with demographic data across various states and districts in India. The objective is to provide insights into transaction trends, device usage, and demographic correlations, while ensuring data consistency and performing advanced analyses to uncover deeper insights.
The datasets span multiple years and quarters, providing a comprehensive view of transactions, user behavior, and demographic details.

---------------------------------------------------------------------------- **Dataset Details:** ----------------------------------------------------------------------------

The data is spread across multiple sheets in an Excel file, each containing different aspects of the transaction and demographic data. Below is an overview of each dataset:

•	**State_Txn and Users:** This dataset contains transaction and user data at the state level. It includes information on the number of transactions, total transaction amount, average transaction value, number of registered users, and app opens.
•	**State_TxnSplit:** This dataset provides a breakdown of transaction types at the state level. It includes information on different transaction types, the number of transactions, total transaction amount, and average transaction value for each type.
•	**State_DeviceData:** This dataset details the device brands used by registered users at the state level. It includes information on the number of registered users per device brand and the percentage of users using each brand.
•	**District_Txn and Users:** This dataset contains transaction and user data at the district level. It includes information on the number of transactions, total transaction amount, average transaction value, number of registered users, and app opens for each district.
•	**District Demographics:** This dataset provides demographic details for each district. It includes information on the population, area, population density, and district headquarters.

---------------------------------------------------------------------------- **Data Dictionary:** ----------------------------------------------------------------------------

Below is the data dictionary for the datasets used in this case study:

1.	**State_Txn and Users**
o	State: Name of the state
o	Year: Year of the data
o	Quarter: Quarter of the year
o	Transactions: Number of transactions
o	Amount (INR): Total amount of transactions in INR
o	ATV (INR): Average transaction value in INR
o	Registered Users: Number of registered users
o	App Opens: Number of app opens

2.	**State_TxnSplit**
o	State: Name of the state
o	Year: Year of the data
o	Quarter: Quarter of the year
o	Transaction Type: Type of transaction (e.g., Recharge & bill payments, Peer-to-peer payments)
o	Transactions: Number of transactions
o	Amount (INR): Total amount of transactions in INR
o	ATV (INR): Average transaction value in INR

3.	**State_DeviceData**
o	State: Name of the state
o	Year: Year of the data
o	Quarter: Quarter of the year
o	Brand: Brand of the device
o	Registered Users: Number of registered users using the brand
o	Percentage: Percentage of registered users using the brand

4.	**District_Txn and Users**
o	State: Name of the state
o	Year: Year of the data
o	Quarter: Quarter of the year
o	District: Name of the district
o	Code: District code
o	Transactions: Number of transactions
o	Amount (INR): Total amount of transactions in INR
o	ATV (INR): Average transaction value in INR
o	Registered Users: Number of registered users
o	App Opens: Number of app opens

5.	**District Demographics**
o	State: Name of the state
o	District: Name of the district
o	Headquarters: District headquarters
o	Population: Population of the district
o	Area (sq km): Area of the district in square kilometers
o	Density: Population density
o	Code: District code
o	Alternate Name: Alternate name of the district

-------------------------------------------------------------------- **Key Findings and Recommendations** --------------------------------------------------------------------

In this project, I explored **PhonePe’s digital payments ecosystem** by analyzing multi-year transaction and demographic datasets across Indian states and districts. Using **Python, Pandas, NumPy, and visualization libraries (Matplotlib and Seaborn)**, I performed **data loading, cleaning, exploratory analysis, and advanced correlation checks** to uncover meaningful insights into user behavior, transaction trends, and device adoption.

**Key Findings:**  
- States with higher registered users and population density generally show higher transaction volumes, though correlation is moderate.  
- High-revenue states often have lower average transaction values, while lower-revenue states show higher-value transactions.  
- Peer-to-peer payments dominate, followed by recharge/bill payments and merchant payments, highlighting concentration in limited modes.  
- Device usage is concentrated in Xiaomi and Samsung, with Samsung leading only in Sikkim.  
- App opens and transaction volumes both show consistent upward trends, reflecting growing user engagement.  

**Recommendations:**  
- Strengthen marketing and infrastructure in high-density states with lower adoption to capture untapped growth.  
- Optimize app performance across diverse device brands beyond Xiaomi and Samsung.  
- Encourage higher-value transactions in low-ATV states through targeted campaigns and promotions.  

This case study demonstrates how **transactional and demographic data can be combined to generate actionable business insights**. It reflects my ability to translate raw data into **strategic recommendations** for digital payment platforms, while showcasing skills in **Python and data visualization**.
