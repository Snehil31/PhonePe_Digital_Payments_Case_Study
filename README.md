📊 **PhonePe Digital Payments Case Study – Transaction & Demographic Analysis**

📌 **Overview**
This case study involves analyzing transaction data from the financial application **PhonePe** along with demographic data across various states and districts in India.  

The objective is to provide insights into:
o	**Transaction trends**
o	**Device usage**
o	**Demographic correlations**

The datasets span multiple years and quarters, offering a comprehensive view of transactions, user behavior, and demographic details.  

In this project, I explored **PhonePe’s digital payments ecosystem** by analyzing multi-year transaction and demographic datasets across Indian states and districts. Using **Python, Pandas, NumPy, Matplotlib, and Seaborn**, I have performed:
o	**Data loading and cleaning**
o	**Exploratory analysis**
o	**Advanced correlation checks**

This case study demonstrates how **transactional and demographic data can be combined to generate actionable business insights**. It reflects my ability to translate raw data into **strategic recommendations** for digital payment platforms, while showcasing skills in **Python and data visualization**.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

📂 **Dataset Details**
The data is spread across multiple sheets in an Excel file, each containing different aspects of the transaction and demographic data:

- **State_Txn and Users:** Transaction and user data at the state level (transactions, amount, ATV, registered users, app opens).  
- **State_TxnSplit:** Breakdown of transaction types at the state level (transaction type, count, amount, ATV).  
- **State_DeviceData:** Device brands used by registered users at the state level (brand, registered users, percentage).  
- **District_Txn and Users:** Transaction and user data at the district level (transactions, amount, ATV, registered users, app opens).  
- **District Demographics:** Demographic details for each district (population, area, density, headquarters).  

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

📖 Data Dictionary

1. **State_Txn and Users**
  o	**State:** Name of the state  
  o	**Year:** Year of the data  
  o	**Quarter:** Quarter of the year  
  o	**Transactions:** Number of transactions  
  o	**Amount (INR):** Total transaction amount  
  o	**ATV (INR):** Average transaction value  
  o	**Registered Users:** Number of registered users  
  o	**App Opens:** Number of app opens  

2. **State_TxnSplit**
  o	**State:** Name of the state  
  o	**Year:** Year of the data  
  o	**Quarter:** Quarter of the year  
  o	**Transaction Type:** Type of transaction (Recharge, P2P, etc.)  
  o	**Transactions:** Number of transactions  
  o	**Amount (INR):** Total transaction amount  
  o	**ATV (INR):** Average transaction value  

3. **State_DeviceData**
  o	**State:** Name of the state  
  o	**Year:** Year of the data  
  o	**Quarter:** Quarter of the year  
  o	**Brand:** Device brand  
  o	**Registered Users:** Number of registered users using the brand  
  o	**Percentage:** Percentage of users using the brand  

4. **District_Txn and Users**
  o	**State:** Name of the state  
  o	**Year:** Year of the data  
  o	**Quarter:** Quarter of the year  
  o	**District:** Name of the district  
  o	**Code:** District code  
  o	**Transactions:** Number of transactions  
  o	**Amount (INR):** Total transaction amount  
  o	**ATV (INR):** Average transaction value  
  o	**Registered Users:** Number of registered users  
  o	**App Opens:** Number of app opens  

5. **District Demographics**
  o	**State:** Name of the state  
  o	**District:** Name of the district  
  o	**Headquarters:** District headquarters  
  o	**Population:** Population of the district  
  o	**Area (sq km):** Area of the district  
  o	**Density:** Population density  
  o	**Code:** District code  
  o	**Alternate Name:** Alternate name of the district
