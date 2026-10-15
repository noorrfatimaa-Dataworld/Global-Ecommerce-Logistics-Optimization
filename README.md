# Global-Ecommerce-Logistics-Optimization
A business-first data analysis project using Google Sheets to identify supply chain fulfillment hubs and calculate e-commerce revenue leakage.
# Global E-Commerce Logistics & Delivery Optimization Report 👗📦

## 📌 Project Overview
Most student data projects focus purely on calculating basic sales metrics. This project takes a corporate, business-first approach to analyze a global **Fashion E-Commerce Store's** transaction data containing over 500k rows. The core objective is to identify logistics operational hubs, isolate areas of revenue leakage due to order cancellations, and prioritize inventory security.

## 🛠️ Tech Stack & Methodology
* **Analytics Engine:** Google Sheets (Cloud Spreadsheet Environment)
* **Logistics Framework:** Supply Chain Optimization & Financial Leakage Tracking
* **AI Collaborator:** ChatGPT (Leveraged for nested logical syntax troubleshooting)

## 🔍 Advanced Business Insights Discovered

### 1. Operational Fulfillment Center Strategy
* **Finding:** By grouping and sorting transactional density by geographical location, the **United Kingdom (UK)** was isolated as the primary logistics hub driving the largest fulfillment volume, processing a massive **4,263,829 units**.
* **Business Action:** Supply chain routes and warehouse capacities should prioritize the UK sector to minimize third-party courier shipping overheads.

### 2. Financial Revenue Leakage Analysis
* **Finding:** Utilizing a customized logical formula (`=IF(Quantity<0, "Cancelled/Returned", "Delivered")`), I calculated the exact financial impact of returned goods. Delivered sales reached **\$10,644,560.42**, while cancellations caused a staggering revenue bleeding of **-\$896,812.49**.
* **Business Action:** Isolating the return rate helps inventory managers audit quality issues or delivery delays in high-return zones to stop profit bleeding.

---
*This portfolio project forms part of my ongoing practical preparation for a 2-month paid Data Science / Data Analytics internship.*
