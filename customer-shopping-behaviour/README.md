# Customer Shopping Behaviour - Customer & Sales Intelligence

## 1. Project Overview

**Goal:**  
Help retail leadership understand who drives revenue, how effective discounts and subscriptions are, and how to better target marketing and operations.

**End-to-End Tech Stack:**
- Data Preparation: Python (pandas, NumPy)
- Analytics & Querying: SQL Server (CTEs, window functions, aggregations)
- Visualization & BI: Power BI (3-page interactive dashboards)
- AI-Enhanced Presentations: Gamma (automatic slide generation from insights)
- Stakeholder Communication: Google Slides (speaker notes, video conversion for async sharing)

**Dataset:**  
~3,900 customer transactions including:
- Demographics: age, gender, location
- Purchase details: item, category, amount, season
- Behaviour: previous purchases, purchase frequency
- Engagement: review rating, discounts, subscription status, shipping, payment method

---

## 2. Business Questions

1. Who drives our revenue across gender, age, location, and category?
2. Are discounts improving revenue quality or just eroding margin?
3. Is the subscription program effectively monetizing loyal customers?
4. How should we optimize operations across shipping and payment channels?

---

## 3. Data Preparation (Python)

**Key Steps:**
- Loaded CSV with pandas and inspected structure
- Fixed 37 missing values in `review_rating` using category-level medians
- Engineered features:
  - `age_group`: Young Adult, Adult, Middle-aged, Senior (quantile-based)
  - `purchase_frequency_days`: Numeric mapping of frequency text (Weekly, Fortnightly, etc.)
- Cleaned column names and dropped redundant `promo_code_used`

**Notebook:** `Customer_Behaviour.ipynb`

---

## 4. SQL Analysis

**10 Key Queries:**
1. Revenue by gender and age group
2. High-value customers using discounts
3. Top 5 products by review rating
4. Average purchase by shipping type
5. Subscribers vs non-subscribers (spend, revenue)
6. Products with highest discount rate
7. Customer segmentation (New/Returning/Loyal)
8. Top 3 items per category
9. Repeat buyers and subscription status
10. Revenue contribution by age group

**File:** `customer.sql`

---

## 5. Power BI Dashboard

**3-Page Report:**

### Page 1: Executive Overview
- KPIs: Total Revenue, Total Customers, Average Review Rating
- Revenue by Location (map)
- Revenue by Age Group, Category, Season, Subscription

### Page 2: Customer Behaviour
- Customers by Age Group and Gender
- Most Purchased Items
- Payment Methods Used
- Purchase Frequency Distribution

### Page 3: Marketing & Retention
- Revenue: Discount vs No Discount
- Subscription vs Revenue
- Average Order Value by Discount
- Shipping & Retention Analysis

**Power BI Report:** `Customer Behaviour Dashboard.pbix`

---

## 6. Key Insights

### Revenue Drivers
- Male customers: 157,890 (68%); Female: 75,191 (32%)
- All age groups contribute 23-27% of revenue
- Clothing & Accessories are core revenue categories

### Discount Performance
- 863 high-value orders use discounts
- AOV uplift from discounts: minimal (~2-3 USD)
- Hat, Coat, Sneakers, Sweater, Pants are promotion-dependent

### Subscription Program
- Penetration: 27.5% subscribed, 72.5% non-subscribed
- AOV is identical for both groups (~59 USD)
- 2,518 repeat buyers (>5 purchases) are not subscribed

### Operations
- Express shipping has slightly higher AOV (~60 vs 58)
- Digital payments (PayPal, cards) dominate

---

## 7. Recommendations

### Revenue & Growth
- Create age-segment playbooks (Young Adults vs Seniors)
- Investigate female funnel and test targeted campaigns
- Treat Clothing & Accessories as hero categories

### Discount Strategy
- Shift to threshold-based discounts ("10% off above X")
- Define door-opener items with higher discounts
- Protect margin on high-review products

### Subscription Program
- Position as loyalty layer (free shipping, early access, VIP support)
- Target repeat buyers (>5 purchases) with conversion offers
- Track "Revenue per Subscriber" metric monthly

### Operations
- Bundle Express/Next Day shipping with subscription tiers
- Optimize operations for most-used shipping methods
- Strengthen partnerships with PayPal and major card networks

---

## 9. How to Use

1. **Run Python notebook:** Load and transform raw CSV data
2. **Execute SQL queries:** Reproduce analytical results in SQL Server
3. **Review Power BI dashboard:** Interact with visualizations and explore insights
4. **Read the business report:** See detailed recommendations and action items

---

## 10. Next Steps

- Implement discount optimisation experiments
- Launch subscription conversion campaign for repeat buyers
- Monitor new KPIs (Discounted Revenue %, Revenue per Subscriber)
- Extend data model to include time-series for trend analysis

---

**Last Updated:** December 2025
