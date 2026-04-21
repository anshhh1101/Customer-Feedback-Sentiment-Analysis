# Customer Feedback Sentiment Analysis Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Dataset-Sample%20Superstore-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

<p align="center">
  A professional Power BI dashboard that integrates customer sentiment analysis with sales and profitability metrics — enabling fast, data-driven business decisions through interactive visualizations.
</p>

---

## Dashboard Preview

<table>
  <tr>
    <td align="center"><b>Page 1 — Customer Sentiment Overview</b></td>
    <td align="center"><b>Page 2 — Profit & Loss Analysis</b></td>
  </tr>
  <tr>
    <td><img src="powerbipro_page-0001.jpg" alt="Customer Sentiment Overview"/></td>
    <td><img src="powerbipro_page-0002.jpg" alt="Profit and Loss Analysis"/></td>
  </tr>
</table>

---

## Table of Contents

- [Problem Statement](#problem-statement)
- [Solution Overview](#solution-overview)
- [Dashboard Pages](#dashboard-pages)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Key Insights](#key-insights)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Problem Statement

Organizations today collect large volumes of customer feedback across multiple channels, yet most lack an efficient way to connect that feedback to actual business outcomes. Without a unified system, identifying which products are underperforming, which regions are losing money, or how discount strategies are impacting profit becomes slow and inconsistent.

**This project addresses the following core challenges:**

- Inability to classify and filter customer sentiment (Positive / Neutral / Negative) alongside business data
- No clear visibility into loss-making products, sub-categories, and geographic regions
- Difficulty understanding how discounts correlate with sales and profitability
- Absence of an interactive, non-technical tool for real-time business monitoring

---

## Solution Overview

A two-page interactive Power BI Dashboard built on the **Sample Superstore** retail dataset. The dashboard links customer sentiment classifications to core KPIs — Sales, Profit, and Orders — and surfaces insights through dynamic, filterable visualizations accessible to any business user.

---

## Dashboard Pages

### Page 1 — Customer Sentiment Overview

Provides a high-level summary of business performance, dynamically filtered by customer sentiment.

| Visual | Description |
|--------|-------------|
| KPI Cards | Total Sales: `1.05M` · Total Profit: `300.18K` · Total Quantity: `4,641` |
| Sentiment Slicer | Toggle between Positive, Neutral, and Negative to update all visuals |
| Bing Map | Geographic sales distribution across cities and regions |
| Scatter Plot | Sales vs. Profit by Product Category |
| Regional Table | Sales and Profit breakdown — South, Central, West, East |
| Pie Chart | Revenue by Segment — Consumer, Corporate, Home Office |
| Funnel Chart | Quantity by Stage — Awareness → Consideration → Purchase |
| Bar Chart | Category-level Sales filtered by selected Sentiment |

### Page 2 — Profit & Loss Analysis

Provides deep profitability insights for identifying problem areas and opportunities.

| Visual | Description |
|--------|-------------|
| Horizontal Bar Chart | Sales vs. Profit comparison across all four regions |
| Scatter Plot | Discount vs. Profit relationship by Category |
| Bar Chart | Profit by Category — Technology `145K` · Office Supplies `122K` · Furniture `18K` |
| Loss Chart | Top loss-making sub-categories — Tables `−17.7K` · Bookcases `−3.5K` · Supplies `−1.2K` |

---

## Key Features

| Feature | Details |
|---------|---------|
| **Sentiment Slicer** | Filters the entire dashboard by customer sentiment in one click |
| **KPI Summary Cards** | Instant snapshot of the three most critical business metrics |
| **Bing Map** | Bubble map showing regional and city-level sales concentration |
| **Scatter Plot Analysis** | Exposes the financial impact of discount strategies at category level |
| **Conditional Formatting** | Green = Profit · Red = Loss — applied consistently for instant readability |
| **Loss Identification Chart** | Quantifies and ranks negative-margin sub-categories to guide corrective action |
| **Segment Distribution** | Pie chart breaking revenue across Consumer, Corporate, and Home Office |
| **Regional Benchmarking** | Side-by-side Sales vs. Profit bars across South, Central, East, and West |

---

## Tech Stack

| Technology | Role |
|------------|------|
| **Power BI Desktop** | Dashboard design, data modeling, and interactive report publishing |
| **DAX** | Custom measures — Total Sales, Total Profit, Total Quantity |
| **Sample Superstore (CSV)** | Source dataset containing Sales, Profit, Discount, Region, Category, Sub-Category, Segment |
| **Bing Maps API** | Built-in Power BI map visual for geographic distribution |

---

## Repository Structure

```
customer-feedback-sentiment-dashboard/
│
├── Customer Feedback Sentiment Analysis.pbix              # Main Power BI dashboard file
├── Customer_Feedback_Sentiment_Analysis_Report.pdf        # Project report (PDF)
├── SampleSuperstore.csv                                   # Source dataset
├── powerbipro_page-0001.jpg                               # Screenshot — Page 1
├── powerbipro_page-0002.jpg                               # Screenshot — Page 2
└── README.md
```

---

## Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) — free download from Microsoft

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/anshhh1101/customer-feedback-sentiment-dashboard.git
cd customer-feedback-sentiment-dashboard
```

**2. Open the dashboard**

Launch `Customer Feedback Sentiment Analysis.pbix` in Power BI Desktop.

**3. Explore sentiment filtering**

On Page 1, use the **Sentiment Slicer** to toggle between Positive, Neutral, and Negative — all visuals update instantly.

**4. Analyze profit & loss**

Navigate to **Page 2** to view the regional profit breakdown and identify the top loss-making sub-categories.

---

## Key Insights

- **East region** leads in both Sales (`3.43M`) and Profit (`1.03M`)
- **Tables** is the single largest loss-making sub-category at `−17.7K`
- **Technology** is the most profitable category at `145K`
- **Consumer** segment drives the largest share of total revenue (~48%)
- High discount rates in the **Furniture** category correlate strongly with low profitability

---

## Future Improvements

- [ ] Real-time database connection for automatic dashboard refresh
- [ ] AI/NLP-powered automatic sentiment classification from raw feedback text
- [ ] Additional slicers for Region, Category, and Time Period (Year / Quarter / Month)
- [ ] Predictive analytics using Power BI forecasting or Azure Machine Learning
- [ ] Mobile-optimized responsive layout for executive access on smartphones

---

## Author

**Anshuman Dev** · [@anshhh1101](https://github.com/anshhh1101)

---

<p align="center">If you found this project useful, consider giving it a ⭐</p>
