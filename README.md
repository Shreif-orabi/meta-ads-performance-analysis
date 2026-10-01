# 📊 Meta Ad Performance Analysis & Campaign Optimization

## 📌 Executive Summary
This project provides an **End-to-End Data Analysis Solution** evaluating paid ad campaigns on **Meta platforms (Facebook & Instagram)**. The main goal is to analyze advertising efficiency across key performance indicators (KPIs), map out user interaction funnels, identify high-converting audience demographics, and optimize budget allocation to maximize **Return on Ad Spend (ROAS)**.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI (Interactive Dashboard, Dynamic Parameters)
* **Data Modeling:** Star Schema Design (1 Fact Table, 3 Dimension Tables)
* **Calculations & Logic:** Advanced DAX (KPI Metrics, CTR, Conversion Rates, Dynamic Metrics)
* **Data Transformation:** Power Query (Data Cleaning, Unpivoting, Custom Columns)
* **Analytics Domain:** Digital Marketing Analytics, Conversion Funnel Analysis, Budget Pacing

---

## 📐 Data Architecture & Schema
The data architecture follows a **Star Schema** centered around the `ad_events` fact table:

* **Fact Table:**
  * `ad_events`: Event logs tracking Impressions, Clicks, Shares, Comments, and Purchases with accurate timestamps.
* **Dimension Tables:**
  * `ads`: Creative metadata (`ad_type`, `ad_platform`, targeting criteria).
  * `campaigns`: Strategic overview (`total_budget`, `start_date`, `end_date`, `duration`).
  * `users`: Demographic profiles (`user_gender`, `age_group`, `country`, `interests`).

---

## 📈 Key Metrics & Performance Highlights
* **Impressions:** 216K (Strong reach across platforms)
* **Clicks:** 25.4K
* **CTR (Click-Through Rate):** **11.76%** *(Well above industry averages (~1-2%), indicating exceptional ad creative performance)*
* **Engagement Rate:** **13.56%** (29K Total Engagements)
* **Conversions (Purchases):** 1.3K Purchases
* **Conversion Rate (from Clicks):** **5.21%**
* **Purchase Rate (from Impressions):** **0.61%**
* **Total Ad Budget:** $2.5M across multiple campaigns (Avg $50.7K/campaign)

---

## 🔍 Core Insights & Findings

### 1. Funnel Efficiency & Drop-Off Leakage
While top-of-funnel reach and engagement are exceptionally strong (CTR 11.76%), the **Purchase Rate drops sharply to 0.61%**. This indicates a **funnel leakage** moving from interest to purchase—likely caused by friction in the landing page experience, audience mismatch, or weak promotional offers.

### 2. Audience & Demographic Profiling
* **Gender:** Females represent **43% of total engagement** (13K interactions), compared to 22% for Males (6K).
* **Age Group:** Engagement peaks sharply in the **18–30 age bracket** (especially early 20s) and drops significantly for audiences aged 35+.
* **Geographics:** **India and Brazil** generate the highest volume of engagement, whereas **Germany and the UK** represent premium, high-purchasing-power segments.

### 3. Ad Formats & Timing Trends
* **Best Performing Ad Formats:** **Video Ads** lead with the highest CTR (11.9%), Conversion Rate (5.2%), and Engagement Rate (13.7%). **Stories** follow closely behind with strong volume. Images and Carousels slightly underperform in conversions.
* **Peak Engagement Hours:** Interactions consistently peak during **late afternoons and evenings (15:00 – 20:00)**, while dropping to minimums during early mornings (00:00 – 05:00).
* **Seasonality:** Campaign spikes occur around specific promotional calendar dates (e.g., 19th–21st, 25th–27th).

---

## 💡 Strategic Business Recommendations
1. **Optimize Conversion Funnel:** Improve landing page load speed, simplify checkout processes, and test retargeting campaigns for users who click but fail to purchase.
2. **Reallocate Ad Budget:** Shift budget allocation towards **Video & Stories formats**, which yield the highest ROI per dollar spent.
3. **Refine Audience Targeting:** Focus core volume acquisition campaigns on **Young Females (18–30)** in high-volume regions (India & Brazil), while crafting specialized high-value value offers for tier-1 markets (Germany, UK, US).
4. **Day-Parting Ad Delivery:** Schedule ad spend weighting during afternoon and evening time windows to capture peak engagement hours.

---

## 📂 Project Structure
```text
├── Data/
│   └── Raw_Dataset_Schema.csv
├── Dashboard/
│   └── Meta_Ads_Performance_Dashboard.pbix
├── Screenshots/
│   └── Dashboard_Overview.png
└── README.md
