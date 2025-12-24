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
- **[View Code](./Customer_Behaviour.ipynb)**

### SQL - Business Queries
- 10 analytical queries (revenue, discounts, products, segments)
- CTEs, window functions, aggregations
- **[View Queries](./customer.sql)**

### Power BI - Interactive Dashboards
- **[Download Dashboard](./Customer\ Behaviour\ Dashboard.pbix)**

**Dashboard Navigation:**

The Power BI dashboard includes a Home page with navigation to 3 main analysis pages:

- **Home** - Project overview with navigation links
- **Executive Overview** - KPIs, revenue by location, age, category, season
- **Customer Behaviour** - Demographics, purchase patterns, payment methods
- **Marketing & Retention** - Discount impact, subscription analysis, shipping insights

**Dashboard Screenshots:**

![Home](./dashboard-screenshots/home.png)
![Executive Overview](./dashboard-screenshots/executive-overview.png)
![Customer Behaviour](./dashboard-screenshots/customer-behaviour.png)
![Marketing & Retention](./dashboard-screenshots/marketing-retention.png)

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

[Complete Methodology](./PRESENTATION_WORKFLOW.md)

---

## 📁 Project Files

| File | Purpose |
|------|---------|
| [customer_shopping_behavior.csv](./customer_shopping_behavior.csv) | Full dataset (3,900 rows) |
| [Customer_Behaviour.ipynb](./Customer_Behaviour.ipynb) | Python data cleaning & analysis |
| [customer.sql](./customer.sql) | 10 SQL business queries |
| [Customer Behaviour Dashboard.pbix](./Customer\ Behaviour\ Dashboard.pbix) | Power BI interactive dashboard with Home page |
| [Customer Behaviour Video.mp4](./Customer\ Behaviour\ Video.mp4) | Presentation video |
| [PRESENTATION_WORKFLOW.md](./PRESENTATION_WORKFLOW.md) | How to create video presentations |

---

## How to Use

1. **View Analysis:** Open [Customer_Behaviour.ipynb](./Customer_Behaviour.ipynb)
2. **Run Queries:** Execute [customer.sql](./customer.sql) on SQL Server
3. **Explore Dashboard:** Download and open [Customer Behaviour Dashboard.pbix](./Customer\ Behaviour\ Dashboard.pbix)
   - Start from Home page for project overview
   - Use navigation to explore each analysis page
4. **Watch Summary:** View [Customer Behaviour Video.mp4](./Customer\ Behaviour\ Video.mp4)

---

**Last Updated:** December 2025
