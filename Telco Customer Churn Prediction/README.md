# <span style="color:crimson;">Telco Customer Churn Prediction

**<span style="color:crimson;">Business Problem**
    
Churn prediction means detecting which customers are likely to leave a service or stop using a product. It is a critical prediction for many businesses because acquiring new clients often costs more than retaining existing ones.  
We need to know: “Is this customer going to leave us within X months?” Yes or No? It is a binary classification task.

![image](https://user-images.githubusercontent.com/83332641/230767917-ffd3edc9-7489-454d-90a9-6bf5a22a103f.png)
    
The data set includes information about:

* Customers who left within the last month – the column is called Churn 
* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies 
* Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges 
* Demographic info about customers – gender, age range, and if they have partners and dependents
    
**<span style="color:crimson;">Task Details**
    
* [1. IMPORTING LIBRARIES AND DATA]
* [2. EXPLORATORY DATA ANALYSIS]
    * [2.1 General Picture](#sub_section-2.1)
    * [2.2 Categorical and Numerical Variable Analysis](#sub_section-2.2)
    * [2.3 Correlation](#sub_section-2.3)
    
 
* [3. FEATURE ENGINEERING & DATA PRE-PROCESSING](#section-three)
    * [3.1 Outliers](#sub_section-3.1)
    * [3.2 Missing Values](#sub_section-3.2)
    * [3.3 Encoding (Label Encoding, One-Hot Encoding)](#sub_section-3.3)
    * [3.4 Feature Extraction & Interactions](#sub_section-3.4)
      
    
* [4. MODEL & PREDICTION](#section-four)
    * [4.1 Base Model](#sub_section-4.1)
    * [4.2 Model with Feature Engineering](#sub_section-4.2)

