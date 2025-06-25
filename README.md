🧾 Supplier Data Quality & GDPR Compliance Dashboard


![image](https://github.com/user-attachments/assets/59b164ec-01dc-409c-af15-aa1e468227d1)
![image](https://github.com/user-attachments/assets/29506273-5598-4af4-9309-7167023e15f0)
![image](https://github.com/user-attachments/assets/89d1baaa-12a0-4a9b-bb2d-c1af971ba947)

📌 Project Objective :
This project showcases my ability to analyze supplier master data with a focus on data quality, freshness, and GDPR compliance.
The use case simulates a luxury industry context, where data accuracy and regulatory compliance are essential. The goal is to deliver a dashboard that supports data governance and drives decision-making.

The dataset used in this project is a simplified simulation. I am aware that the real world, involves much larger volumes, more varied data, and more complex business rules.

This approach aims to demonstrate my ability to translate business challenges into relevant and actionable indicators, as well as my mastery of data engineering and visualization tools.

🛠️ Tech Stack
🐍 Python / Jupyter Notebook: Synthetic data generation and KPI calculations

📊 Power BI: Interactive dashboard creation

💾 CSV: Supplier dataset

🧠 Business logic for quality scoring and compliance checks

🧱 Project Structure
1. Data Simulation (Python)
- Created a dataset of 1,000 suppliers

- Fields: Supplier Name, Email, VAT Number, Country, Compliance_RGPD, Last Updated Date

- Random but realistic value assignment for each field

2. KPI & Score Calculation
Data Quality Score (0 to 100), based on:

- Valid Email

- VAT Number present

- Valid Country

- GDPR Compliance = “Yes”

- Additional KPIs:

  - Email completion rate

  - VAT completion rate

  - % of GDPR compliant records

  - Average age of data (last update)

% of records updated within the last year

3. Power BI Dashboard
- Three interactive pages:

🧭 Executive Summary
- High-level KPIs

- World map by country

- Global completion & compliance rates

- Data freshness indicator (average age)

🧪 Data Quality
- Quality score distribution

- Attribute-level completion stats

- Country-level quality map

✅ GDPR Compliance
- GDPR compliance heatmap by country

- Focus on non-compliant suppliers

🎯 Key Takeaways
- Applied data governance principles

- Included data freshness as a decision factor

- Built a dashboard with clear storytelling

Some calculations in this project have been simplified for demonstration purposes; in an industrial context, these verifications would be complemented by formal validation processes to ensure higher data quality.

🚀 Next Steps (improvements)
- Add a relational data model

- Expand with supplier contracts or purchase orders

- Automate the pipeline with scheduling and monitoring tools

