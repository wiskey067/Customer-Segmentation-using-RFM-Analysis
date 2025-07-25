

Customer-Segmentation-using-RFM-Analysis




# 📊 Customer Segmentation using RFM Analysis

This project demonstrates customer segmentation for an e-commerce business using the **RFM (Recency, Frequency, Monetary)** model. By analyzing purchasing behavior, we segment customers into distinct groups to support targeted marketing, improve retention, and boost revenue.

---

## 📁 Project Overview

- **Developer**: Arijit Bhattacharjee  
- **Tools Used**:
  - **Python** (for data cleaning, RFM scoring, and customer segmentation)
  - **Power BI** (for creating a dynamic, interactive dashboard)
- **Dataset Source**: Kaggle - E-commerce Dataset  
- **Data Size**: 541,909 rows, 8 columns  

---

## 🔧 Python Libraries Used

python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

  •	Pandas & NumPy: For data manipulation and numerical operations
	•	Seaborn & Matplotlib: For EDA and visualizations
	•	Jupyter Notebook: To implement and document the RFM logic

⸻

🔍 RFM Analysis Logic

RFM stands for:
	•	Recency: Days since the last purchase
	•	Frequency: Total number of transactions
	•	Monetary: Total amount spent

Each customer is scored (1 to 5) on all three metrics. The combination of these scores is used to segment customers into categories such as:
	•	High Value
	•	Loyal
	•	At Risk
	•	Dormant

⸻

📊 Power BI Dashboard

Once the RFM scores were generated in Python, the final dataset was exported and used to create a Power BI Dashboard featuring:
	•	RFM Score Distribution
	•	Segment Heatmaps
	•	Customer Lifetime Value Analysis
	•	Targeted Recommendations by Segment

⸻

🧾 Files Included
	•	rfm_analysis.ipynb – Python notebook for RFM scoring
	•	cleaned_rfm_dataset.csv – Final processed dataset for visualization
	•	PowerBI_RFM_Dashboard.pbix – Interactive Power BI dashboard file
	•	README.md – Project documentation

⸻

🧠 Key Insights
	•	~26% of customers contribute to 80% of total revenue (Pareto Principle)
	•	Customers were segmented into clear behavioral groups for marketing actions
	•	Power BI enabled an interactive way to explore and present business insights

⸻

📬 Contact

Arijit Bhattacharjee
📧 ab9777816@gmail.com
📞 +91-9073930881


