# 🛒 Customer Purchase Behavior Analysis with Hadoop

## 📌 Overview

In today’s fast-paced retail world, **data alone isn’t enough** — insights drive decisions. This project **transforms over 100,000 raw e-commerce records** from Target’s Brazilian operations into a **strategic roadmap for growth**, turning complex data into actionable business intelligence. Leveraging **Cloud Computing and Big Data frameworks**, it **decodes consumer behavior, uncovers patterns, and provides clear recommendations** to optimize operations and boost revenue.  

### Project Objectives
The project focuses on three key objectives:

1. **Analyze Customer Purchasing Behavior**  
   Understand how often customers buy, what drives their decisions, and uncover patterns in their shopping habits.

2. **Identify Customer Preferences**  
   Track spending trends across product categories, payment methods, and timing to reveal what influences purchasing decisions.

3. **Segment Customers Based on Behavior and Demographics**  
   Group customers by geography, purchase frequency, and payment preferences to enable **targeted strategies** for different segments.

**Dataset:** [Brazilian E-Commerce Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 🛠 Technical Framework
To handle the **volume and variety of e-commerce data**, the project utilized a robust **Hadoop ecosystem** for scalable and precise data management:

![Hadoop Framework Diagram](https://via.placeholder.com/800x400.png?text=Hadoop+Framework+Diagram)

- **Distributed Storage (HDFS)**: Primary repository for high-volume datasets, ensuring durability and reliability.  
- **Metadata Management (Apache HCatalog)**: Standardized data definitions across the stack, enabling seamless interoperability between tools.  
- **Data Transformation (Apache Pig)**: Automated data cleaning, removed over **14,000 duplicate entries**, and handled missing values to maintain integrity.  
- **Analytical Querying (Apache Hive)**: Performed SQL-style joins across **Customers, Orders, and Payments tables** to generate a unified view of retail operations.  
- **Visualization & BI (Power BI)**: Converted processed data into **dynamic dashboards**, providing executive-level insights.

---

## 📊 Strategic Business Insights
The analysis uncovered key trends and performance drivers in the Brazilian retail market:

- **Seasonal Revenue Cycles**: Revenue peaks in **November and December**, confirming Black Friday and year-end holidays as primary drivers of **$8.73M annual revenue**.  
- **Category Dominance**: **Home & Living (26.9%)** and **Sports & Outdoors (19.7%)** emerged as top sectors, highlighting lifestyle and wellness-focused consumer behavior.  
- **Regional Payment Habits**: Preference for **credit card installments**, reflecting financial flexibility as a requirement for high-value conversions.  
- **The Retention Gap**: Approximately **37,000 one-time buyers** identified, revealing a major opportunity for targeted re-engagement strategies.

---

## 💡 Data-Driven Recommendations
Based on the insights, three core strategic actions were proposed:

1. **Retention Engineering**: Implement automated **CRM sequences** and loyalty incentives to convert one-time purchasers into repeat customers.  
2. **Predictive Inventory Management**: Adjust stock levels for top categories (**Home & Living**) **60 days before the Q4 surge**.  
3. **Checkout Optimization**: Streamline installment payments and **voucher redemption** to reduce friction during high-intent purchase periods.

---

## ✅ Conclusion
This case study demonstrates the **successful integration of Hadoop-based processing with BI visualization**. By moving beyond traditional data silos, it provides a **clear, actionable blueprint** for Target to enhance market positioning and maximize **customer lifetime value** in the Brazilian e-commerce sector.
