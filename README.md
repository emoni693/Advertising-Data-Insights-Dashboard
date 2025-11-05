# Advertising Data Insights Dashboard

## Task 2: Social Media Campaign Performance Tracker

##  Objective  
Analyze multi-channel ad campaign data (Facebook, Instagram, TV, Google Ads, etc.) to evaluate:  
- Performance  
- Engagement  
- Click-Through Rate (CTR)  
- Return on Investment (ROI)

---

## 🧠 Skills Gained  
- Marketing Analytics  
- Campaign Optimization  
- Dashboard Storytelling  

---

## 🧰 Tools Used  
- **Power BI** (primary dashboard tool)   
- **Excel / Google Sheets** (data cleaning or quick exploration)  

## 🗂️ Dataset  
**Name:** Social Media Ads – Click Prediction Dataset  
**File:** `Advertising_Data.csv`  
**Source:** [Google Drive Link](https://drive.google.com/file/d/1qw0-IGpGsGfZ0df6W9O_cZR18Kav__5x/view?usp=sharing)  

**Columns Include:**  
- `TV`  
- `Billboards`  
- `Google_Ads`  
- `Social_Media`  
- `Influencer_Marketing`  
- `Affiliate_Marketing`  
- `Product_Sold`  

Each row represents the marketing spend across multiple channels and the corresponding number of products sold.

---

## 🚀 Deliverables  
Create a **polished Power BI dashboard** (or Google Looker Studio report) that includes:  
- **Overview of Campaign KPIs** — Total Spend, Total Sales, ROI, CTR  
- **Insights into Top-Performing Channels**  
- **ROI Summary** — Channel-wise comparison of investment vs. return  
- **Interactive Filters** — by channel, region, device, or campaign  
- **Actionable Recommendations** — based on insights  

---

## 🪜 Getting Started  

### Step 1: Download Data  
- Download the dataset from [Google Drive](https://drive.google.com/file/d/1qw0-IGpGsGfZ0df6W9O_cZR18Kav__5x/view?usp=sharing).  
- Save it locally as `Advertising_Data.csv`.

### Step 2: Import into Power BI  
- Open **Power BI Desktop**  
- Go to **Home → Get Data → Text/CSV → Browse** and select `Advertising_Data.csv`

### Step 3: Data Transformation  
In **Power Query Editor**:  
1. Check column data types (Number, Text, etc.)  
2. Add calculated columns (e.g., `Total_Spend`, `ROI`)  
3. Optionally **Unpivot** ad spend columns to analyze channel-level data  

### Step 4: Build Measures & KPIs  
Examples:
```DAX
Total Spend = SUM(Advertising_Data[Total_Spend])
Total Sales = SUM(Advertising_Data[Product_Sold])
ROI = DIVIDE([Total Sales], [Total Spend])



