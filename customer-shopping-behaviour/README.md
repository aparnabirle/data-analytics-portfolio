# Customer Shopping Behaviour - Customer & Sales Intelligence

## Project Overview

**Goal:** Understand revenue drivers, discount effectiveness, and subscription impact.

**Tech Stack:**
- Data Preparation: Python (pandas)
- Analytics: SQL Server (CTEs, window functions)
- Visualization: Power BI (3-page interactive dashboards)
- Presentations: Gamma AI → Google Slides → Video

**Dataset:** 3,900 customer transactions (18 attributes)

---

## Business Questions

1. Who drives revenue across gender, age, and category?
2. Are discounts improving revenue quality or eroding margin?
3. Is the subscription program monetizing loyal customers?
4. How to optimize shipping and payment operations?

---

## Analysis Workflow

### Python - Data Preparation
- Cleaned missing values (37 in review_rating)
- Feature engineering: age_group, purchase_frequency_days
- [View: `Customer_Behaviour.ipynb`]

### SQL - Business Queries
- 10 analytical queries (revenue, discounts, products, segments)
- CTEs, window functions, aggregations
- [View: `customer.sql`]

### Power BI - Interactive Dashboards

**Page 1: Executive Overview**
![Executive Overview](dashboard-screenshots/executive-overview.png)

**Page 2: Customer Behaviour**
![Customer Behaviour](dashboard-screenshots/customer-behaviour.png)

**Page 3: Marketing & Retention**
![Marketing & Retention](dashboard-screenshots/marketing-retention.png)

---

## Key Findings

| Insight | Finding |
|---------|---------|
| Revenue by Gender | Male: $157.9K (68%), Female: $75.2K (32%) |
| Top Products | Blouse, Jewelry, Pants |
| Discount Impact | Used on 863 high-value orders, minimal AOV uplift |
| Subscription | 27.5% penetrated, no spend difference vs non-subscribers |
| Repeat Buyers | 2,518 loyal customers (>5 purchases) not subscribed |

---

## Recommendations

✅ **Revenue Growth:** Age-targeted campaigns, female funnel optimization  
✅ **Discount Strategy:** Threshold-based discounts, protect high-margin items  
✅ **Subscription:** Position as loyalty program, convert repeat buyers  
✅ **Operations:** Bundle shipping with subscription, optimize digital payments  

---

## Modern Presentation Workflow

**Gamma AI → Google Slides → Video**

1. Gamma auto-generates slides from insights
2. Google Slides refinement + speaker notes
3. Convert to MP4 video for async sharing

[See: `PRESENTATION_WORKFLOW.md` for complete methodology]

---

## Files

- `customer_shopping_behavior.csv` - Full dataset
- `Customer_Behaviour.ipynb` - Python analysis
- `customer.sql` - SQL queries
- `Customer Behaviour Dashboard.pbix` - Power BI
- `Customer Behaviour Video.mp4` - Presentation video

---

## How to Use

1. Run Python notebook to clean data
2. Execute SQL queries on your database
3. Open Power BI dashboard
4. Watch video for executive summary

---

**Last Updated:** December 2025
