#  Supply Chain Performance Analysis

An interactive Excel dashboard analyzing supply chain data across 10 business dimensions — identifying quality risks, cost inefficiencies, and supplier performance gaps.

---
**🔗 Live Dashboard:** [View on Google Spreadsheet](https://docs.google.com/spreadsheets/d/1iq88_RX-O2P7aOVnlRnaHvtlUQXTZDna/edit?usp=sharing&ouid=113370789229794763814&rtpof=true&sd=true)

##  Dashboard Overview

| KPI | Value |
|---|---|
| Total Products Analyzed | 100 SKUs |
| Total Revenue Generated | $577,605 |
| Average Defect Rate | 2.28% |
| Average Lead Time | 17.1 days |

---

## 🔍 Business Questions Answered

1. Which product type generates the highest total revenue?
2. Which product type has the highest manufacturing cost vs revenue ratio?
3. Which supplier has the highest average defect rate?
4. Which product type has the most inspection failures?
5. Which product type has the lowest stock levels despite high sales volume?
6. What is the average stock level per product type?
7. Which transportation mode has the lowest average shipping cost?
8. Which shipping carrier is used most frequently?
9. Which supplier has the shortest average lead time?
10. Which supplier handles the highest production volume?

---

##  Key Insights

- **Skincare** generates the highest revenue ($241,628) but also has the highest manufacturing costs
- **Supplier 5** has the highest average defect rate — a quality control risk
- **Supplier 1** has the shortest lead time — most reliable for urgent orders
- **Cosmetics** has the highest stock levels relative to sales — potential overstock issue
- **Air transport** has the highest shipping cost — opportunity to optimize logistics

---

##  Tools Used

- **Microsoft Excel** — Pivot Tables, Charts, KPI Cards, Slicers
- **Functions** — AVERAGE, SUM, COUNTA, cross-sheet references
- **Visualization** — Bar charts, Clustered bar charts, Donut chart
- **Interactivity** — Product type slicer connected to all 10 pivot tables

---

## Dashboard Structure

| Sheet | Content |
|---|---|
| Products Table | Raw data source |
| Revenue | PT1 — Total Revenue by Product Type |
| Defects | PT2 — Average Defect Rate by Supplier |
| Shipping Cost | PT3 — Average Shipping Cost by Transport Mode |
| Stock vs Sales | PT4 — Stock Levels vs Products Sold |
| Mfg Cost vs Revenue | PT5 — Manufacturing Cost vs Revenue |
| Inspection Failure by prod | PT6 — Inspection Results by Product Type |
| Avg Stock lvl by prod type | PT7 — Average Stock Level by Product Type |
| Shipping Cost by carrier | PT8 — Orders by Shipping Carrier |
| Lead Time By supplier | PT9 — Average Lead Time by Supplier |
| Production Volume by Supplier | PT10 — Production Volume by Supplier |
| **Dashboard** | **Interactive summary with KPI cards + slicer** |

---

## 📂 Data Source

[Supply Chain Analysis Dataset](https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis) — Kaggle

---

## 👩‍💻 Author

**Hasnay Hasin**
- Portfolio: [hesney-hasin-portfolio.netlify.app](https://hesney-hasin-portfolio.netlify.app)
- LinkedIn: [hesney-hasin-maliha](https://www.linkedin.com/in/hesney-hasin-maliha/)
