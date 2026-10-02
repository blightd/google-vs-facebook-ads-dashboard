# 📊 Google Ads vs. Facebook Ads Performance Dashboard

An interactive Excel analytics dashboard comparing campaign performance metrics across Google Ads and Facebook Ads. This project analyzes campaign spend efficiency, audience engagement, and channel-specific conversion mechanics.
---

## 📷 Raw File Preview

![Full Raw File Overview](Screenshrots/raw_data.png)

---
---

## 📷 Dashboard Preview

![Full Dashboard Overview](Screenshrots/G-vs-F.png)

---

## 💡 Key Performance Indicators (KPIs)

Below is the consolidated performance summary across both platforms:

![KPI Summary Cards](Screenshrots/KPI-ss.png)

| Metric | Calculated Value | Formula / Method |
| :--- | :--- | :--- |
| **Total Spend** | ₹ 25,03,118.77 | `SUM(spends)` |
| **Total Impressions** | 48,47,505 | `SUM(impressions)` |
| **Total Clicks** | 2,01,634 | `SUM(clicks)` |
| **Overall CTR** | 4.16% | `SUM(clicks) / SUM(impressions)` |
| **Overall CPC** | ₹ 12.41 | `SUM(spends) / SUM(clicks)` |

---

## 🔍 Dataset & Channel Structure

The raw dataset contains multi-channel marketing data with platform-specific fields:

* **Common Attributes:** `Date`, `Age`, `Spends`, `Impressions`, `Clicks`, `CPC`, `CTR`, `CPM`
* **Google Ads Specific:** `Device` (Desktop/Mobile), `Subchannel` (Brand/Non-Brand)
* **Facebook Ads Specific:** `Creative Name`, `Creative Type`, `Link Clicks`, `CPA`

---

## 📈 Dashboard Features & Analytics

### 1. Platform Efficiency Breakdown
![Platform Comparison](Screenshrots/fcebook_mkt.png)
* **Cost Per Click (CPC) vs. CPM Analysis:** Evaluates which platform delivers cheaper impression reach vs. higher click intent.
* **Demographic Target Analysis:** Evaluates campaign spend distribution across age brackets (`18-24`, `25-34`, `35-44`, etc.).

### 2. Interactive Slicers & Filters
* **Platform Filter:** Toggle seamlessly between Google Ads, Facebook Ads, or combined view.
* **Campaign Type & Subchannel:** Drill down into specific marketing funnels.
* **Timeline Slicer:** Dynamically filter performance trends across custom date ranges.

---
