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

## 🛠 Hadoop Ecosystem
To handle the **volume and variety of e-commerce data**, the project utilized a robust **Hadoop ecosystem** for scalable and precise data management:

<p align="center">
  <img src="images/hadoop-framework.png" width="650">
</p>

- **Environment**: Deployed using **Hortonworks 2.1** on **Oracle VirtualBox**, with **PuTTY** for SSH access and **WinSCP** for secure file transfers between the local machine and the Hadoop cluster.

- **Data Storage & Management**: **HDFS** serves as the primary storage layer for large-scale datasets, while **Apache HCatalog** standardizes metadata to ensure consistent and seamless data access across all processing tools.

- **Processing & Querying**: **Apache Hive** acts as the primary analytical engine. Its SQL-like interface enables efficient querying and joining of **six interconnected datasets** (Customers, Orders, Products, Payments, etc.), while also supporting data cleaning tasks such as the removal of **14,056 duplicate records**.

- **Data Transformation**: **Apache Pig** handles high-level data scripting and preprocessing, simplifying complex transformation logic and improving data readiness for analysis.

- **Visualization & BI**: **Power BI** integrates with the processed datasets to create **interactive dashboards**, enabling real-time monitoring of trends, patterns, and key business metrics.

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
