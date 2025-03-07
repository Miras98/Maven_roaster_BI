# ☕ Maven Roaster Analysis  

## 📌 Overview  
The **Maven Roaster Analysis** project performs advanced analysis using DAX to examine
**sales trends, customer behavior, and product performance** using data from a coffee roastery business.
By analyzing transactional and inventory data, we uncover key insights that drive business decisions.  

## 📊 Objectives  
- Identify **sales trends** across time, customers, and products  
- Analyze **customer behavior** to improve retention and marketing strategies  
- Evaluate **product performance** and **inventory management**  
- Leverage data insights for **better business decision-making**  

## 🗂 Dataset Description  
The analysis is based on the following tables:  
- **`calendar`** → Provides time-based insights on sales trends
- **`Sales by Store`** → fact table that involves measures such as unit price, quantity sold and orders
- **`food inventory`** → fact table that tracks inventory levels and stock movements  
- **`customer lookup`** → Contains customer demographics and segmentation  
- **`product lookup`** → Stores product details like category, price, and type
- **`Employee lookup`** → contains employees info. like name, location ,and position


  ## 📸 **Dashboard Preview**  

![Maven_overview](https://github.com/user-attachments/assets/ba3043de-8382-41d4-997f-60f71d2e5ac4)

## **Key Findings & Business Recommendations**  

### **1️⃣ Sales Trends**  
- **Total Sales & Growth**: The total sales amount is **$4.25M**, with the highest Month-over-Month (MoM) growth of **27.91% in April**.  
  - 📌 **Recommendation:** Leverage marketing efforts around April, analyze reasons for the surge, and replicate successful strategies in other months.  

- **Profit Over Time**: The **highest profit was in 2018** ($1.41M).  
  - 📌 **Recommendation:** Assess the factors contributing to this peak—pricing, demand, or economic trends. 

- **Sales Contribution by Store & Employee**:  
  - **Store 8** generated the highest sales percentage (**33.44%**).  
  - **Top Sales Employees**: **Britanni Jordan, Kylie Candace, and Joelle Christen**.  
  - 📌 **Recommendation:** Incentivize top performers with commissions or recognition programs. Analyze the strategies of Store 8
    and apply best practices to lower-performing stores.  

- **Sales on Weekends vs. Weekdays**:  
  - **71.41% of sales occur on weekdays**, while **28.59% happen on weekends**.  
  - 📌 **Recommendation:** Introduce **weekend-specific promotions** or special events to boost weekend sales.  

---

### **2️⃣ Customer Insights**  
- **Customer Segments & Memberships**:  
  - The most **frequent buyers** are **loyal customers aged 40-50**.  
  - **Member customers** contribute to **49.02% of total sales**.  
  - 📌 **Recommendation:** Strengthen **loyalty programs** for this age group and promote **membership benefits** to non-members to increase retention and spending.  

- **Most Profitable Customers**:  
  - **Summer, Meghan, and Peter** contribute the highest profits.  
  - 📌 **Recommendation:** Offer them **exclusive deals, personalized promotions**, and VIP perks to **encourage repeat purchases**.  

---

### **3️⃣ Product Performance**  
- **Best-Selling Products**:  
  - **Sustainably Grown Organic Lg, Dark Chocolate Lg, and Latte Rg** are the top 3 best-sellers.  
  - 📌 **Recommendation:** Ensure **stock availability**, optimize **pricing**, and highlight these items in marketing campaigns.  

- **Sales by Product Group per Store**:  
  - **Beverages** lead in **Store 3 (34.21%)**, **Food** dominates **Store 5 (34.49%)**, and **Whole Bean/Teas** contribute to **42.55% of Store 8’s sales**.  
  - 📌 **Recommendation:** Tailor **inventory and promotions** based on store-specific demand.  

- **7-Day Rolling Average Profit**:  
  - **Beverages and Food** show an **upward trend**, indicating **growing demand**.  
  - **Add-ons and Merchandise** have a **flat trend**, showing **consistent but stagnant demand**.  
  - 📌 **Recommendation:** Increase focus on **Beverages and Food** through advertising,
     while testing **new product variations or bundling strategies** for Add-ons and Merchandise.  

---

### **4️⃣ Food Inventory Management**  
- **Unsold Food & Lost Revenue**:  
  - **Store 3** had the highest **unsold food inventory ($169,934)**.  
  - **Scone and Oatmeal Scone** products contribute the most to lost revenue.  
  - 📌 **Recommendation:** Improve **demand forecasting**, adjust **ordering strategies**,
    and introduce **discounts or promotions** for perishable food items close to expiration.  

---

## **Final Business Recommendations**
✅ Optimize marketing strategies based on **seasonal and product demand trends**.  
✅ Strengthen **loyalty programs and membership incentives** to **increase repeat purchases**.  
✅ Reduce food waste by **enhancing inventory planning and promotional pricing**.  
✅ Scale **best practices** from high-performing stores and employees to **improve sales in weaker areas**.  
