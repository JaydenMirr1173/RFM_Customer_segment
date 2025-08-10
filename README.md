# ​ RFM Customer Segmentation

## Overview
This project applies **RFM (Recency, Frequency, Monetary)** analysis on customer data to segment them into actionable groups: **VIP**, **Loyal**, **Potential**, and **At Risk**. These segments enable businesses to tailor marketing campaigns and improve customer retention strategies.

## Dataset
- **File**: `marketing_campaign.csv`
- Each row includes customer demographics, purchase behavior, and campaign response data.

### Key Columns
- `ID` – Unique customer identifier  
- `Dt_Customer` – Date when the customer enrolled  
- Demographics: `Year_Birth`, `Marital_Status`, `Income`, `TotalChildren` (combined kids & teens)  
- Purchase metrics: `MntWines`, `MntFruits`, ..., `TotalSpent`  
- Frequency metrics: `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`  
- RFM metrics: `Recency`, `Frequency`, `Monetary`

## Tech Stack
- **Python**  
- **Pandas** – Data manipulation and analysis

## How to Run
```bash
git clone https://github.com/JaydenMirr1173/RFM_Customer_segment.git
cd RFM_Customer_segment
pip install pandas
jupyter notebook RFM_CUSTOMER_SEGMENTS.ipynb
