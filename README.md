# 📊 Python-Based Data Analysis Projects

A collection of end-to-end **Python Data Analysis and Exploratory Data Analysis (EDA)** projects focused on transforming raw datasets into business insights and actionable recommendations.

---

# 1. 🛒 Amazon Sales & Order Performance Analysis

## 🎯 Executive Problem

Analyze Amazon order-level data to understand **revenue performance, product contribution, order outcomes, fulfilment performance, promotions, geographic concentration, SKU performance, and operational risks**.

The analysis covers **120,352 orders and 116,648 units**, generating approximately **₹7.86 Cr in recorded gross revenue**.

---

## 💼 Business Problem

The business needs to understand:

- Which product categories drive the majority of revenue?
- Which states contribute the most revenue?
- What percentage of orders are cancelled or returned/failed?
- Which fulfilment method has better order outcomes?
- Which SKUs generate high revenue but also carry high operational risk?
- Do promotions have an association with higher transaction values?
- Where are data-quality and financial anomalies present?

---

## 🔎 Methodology

### 1. Data Profiling & Cleaning
- Dataset structure and data-type validation
- Duplicate detection and removal
- Missing-value analysis
- Postal-code cleaning
- City-name normalization
- Categorical consistency checks
- Numeric validation
- Amount and quantity anomaly investigation

### 2. Feature Engineering
Created analytical fields for:
- Order-level revenue
- Order outcome groups
- Cancellation status
- Return/failed-delivery status
- Promotion status
- Revenue classification
- SKU performance metrics

### 3. Business Analysis
Performed:
- Order-level analysis
- Product/category analysis
- SKU analysis
- Size analysis
- Time-series analysis
- Geography analysis
- Cancellation analysis
- Return/failure analysis
- Promotion analysis
- B2B vs B2C analysis
- Fulfilment analysis

### 4. Advanced Analysis
- ABC / Pareto analysis
- SKU performance segmentation
- SKU risk segmentation
- Promotion × order outcome analysis
- Statistical testing
- Anomaly detection
- Executive KPI framework

---

## 🛠️ Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Time-Series Analysis
- Pareto / ABC Analysis
- Segmentation
- Anomaly Detection
- Business Analysis

---

## 📈 Results & Business Recommendations

### Key Results

- **120,352 orders** analyzed.
- **116,648 units** sold.
- Approximately **₹7.86 Cr recorded gross revenue**.
- **Set, Kurta and Western Dress** together contribute approximately **91.25% of recorded revenue**.
- The top five states contribute approximately **56.08% of revenue**.
- **14.29% cancellation rate**.
- **1.66% return/failed-delivery rate**.
- Combined negative outcome rate is approximately **15.95%**.
- Merchant fulfilment has a **23.05% negative outcome rate**, compared with **12.87% for Amazon fulfilment**.
- **379 high-revenue/high-risk SKUs** contribute approximately **13.31% of revenue**.
- Approximately **27.42% of SKUs contribute 80% of recorded revenue**.
- Promotional transactions have a higher average transaction amount (**₹674.22 vs ₹599.61**), although this represents an association rather than proof of causation.
- The analysis identified **3,600 statistical amount outliers** and **126 records with positive quantity but missing amount**.

### Business Recommendations

**1. Investigate Merchant Fulfilment**

The higher negative-outcome rate for merchant-fulfilled orders indicates an important operational investigation area.

**2. Protect Core Revenue Categories**

Set, Kurta and Western Dress generate the majority of revenue. Inventory availability, fulfilment quality and operational monitoring should receive greater attention for these categories.

**3. Prioritize High-Revenue High-Risk SKUs**

The 379 high-revenue/high-risk SKUs should be investigated at SKU level, particularly where cancellation and return/failure rates are elevated.

**4. Evaluate Promotions Carefully**

Promoted transactions show higher average transaction values, but category, SKU and fulfilment mix should be controlled before concluding that promotions caused the increase.

**5. Improve Data Quality Monitoring**

Missing amounts, unusual quantities and statistical outliers should be investigated through source-system validation before financial or operational decisions are made.

---

# 2. 🛍️ Customer Shopping Behavior Analysis

## 🎯 Executive Problem

Analyze customer shopping behavior to understand **customer demographics, product preferences, revenue contribution, subscription behavior, discounts, payment methods, shipping preferences, purchase frequency and customer segments**.

---

## 💼 Business Problem

The business needs to understand:

- Which product categories generate the most revenue?
- Who are the highest-value customer segments?
- How does gender contribute to revenue?
- Does subscription status increase customer spending?
- Are discounts and promo codes increasing average purchase value?
- Which payment and shipping methods are most popular?
- How do customer demographics relate to purchasing behavior?
- Can customers be segmented based on spending and loyalty?

---

## 🔎 Methodology

### 1. Data Cleaning

- Missing-value validation
- Duplicate removal
- Column-name standardization
- Data-type correction
- Yes/No field standardization
- Category consistency checks

### 2. Exploratory Data Analysis

Analyzed:

- Age
- Purchase Amount
- Review Rating
- Previous Purchases
- Product categories
- Products
- Size
- Color

### 3. Revenue Analysis

Revenue was analyzed by:

- Category
- Gender
- Location
- Season
- Age group
- Subscription status
- Payment method

### 4. Customer Behavior Analysis

Performed:

- Subscription analysis
- Discount analysis
- Promo-code analysis
- Payment-method analysis
- Shipping analysis
- Purchase-frequency analysis

### 5. Customer Segmentation

Created:

- Purchase Amount Segments
  - Low Spenders
  - Medium Spenders
  - High Spenders

- Loyalty Segments
  - New
  - Occasional
  - Regular
  - Loyal

### 6. Advanced Analysis

- Correlation analysis
- Gender × Category analysis
- Age Group × Category analysis
- Season × Category analysis
- Subscription × Purchase Amount
- Discount × Purchase Amount
- Location × Revenue
- Payment × Customer behavior

---

## 🛠️ Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Exploratory Data Analysis
- Customer Segmentation
- Correlation Analysis
- Revenue Analysis
- Demographic Analysis
- Business Analysis
- Data Visualization

---

## 📈 Results & Business Recommendations

### Key Results

**1. Category Performance**

Clothing is the strongest revenue-generating category, contributing more than **$104,000**, followed by Accessories at approximately **$74,200**.

**2. Gender Revenue Distribution**

Male customers generate approximately **$157,890** in revenue compared with approximately **$75,191** from female customers.

However, average transaction values are very similar:

- Male: **$59.54**
- Female: **$60.25**

This indicates that the revenue difference is primarily associated with transaction/customer volume rather than substantially different average basket values.

**3. Subscription Performance**

Subscribers and non-subscribers have very similar average purchase values:

- Subscribers: approximately **$59.49**
- Non-subscribers: approximately **$59.87**

The analysis therefore does not show a meaningful increase in transaction value associated with subscription status.

**4. Discount & Promo Performance**

Average purchase value does not increase with promotions:

- Without promotion: approximately **$60.13**
- With promotion: approximately **$59.28**

**5. Age Segment**

The **56+ age group** is the largest revenue-contributing age segment, generating approximately **$69,590**.

**6. Correlation Findings**

The analysis found:

- Previous purchases have almost no linear relationship with current purchase amount.
- Age has almost no linear relationship with purchase amount.
- Review rating has no meaningful linear relationship with purchase amount.

### Business Recommendations

**1. Expand Female Customer Acquisition**

Female customers generate substantially lower total revenue despite having a slightly higher average transaction value. Targeted campaigns and product-specific marketing can be used to investigate and address this segment gap.

**2. Redesign Loyalty & Subscription Benefits**

Since subscribers do not show higher average transaction values, the loyalty program should be evaluated for its ability to increase basket size and customer value.

Possible approaches include:

- Tiered rewards
- Higher-value basket incentives
- Exclusive benefits
- Reward points based on spending thresholds

**3. Optimize Discount Strategy**

Flat discounts should be evaluated carefully because promotional transactions do not show higher average purchase values in this dataset.

Bundle-based promotions and targeted offers can be tested instead of broad discounts.

---

# 3. 🚖 NYC Yellow Taxi Trip Analysis

## 🎯 Executive Problem

Analyze NYC Yellow Taxi trip data to understand **trip demand, revenue, fare behavior, travel distance, trip duration, payment behavior, passenger patterns, time-based demand and location-level activity**.

The cleaned dataset contains approximately **3.47 million trips**.

---

## 💼 Business Problem

Taxi operators and transportation stakeholders need to understand:

- When is taxi demand highest?
- Which hours generate the most revenue?
- How do weekday and weekend patterns differ?
- What are the typical trip distance and duration?
- Which time periods require greater fleet availability?
- How does payment type relate to revenue and tipping?
- Which passenger groups and distance segments contribute to revenue?
- Which pickup locations generate the highest demand?

---

## 🔎 Methodology

### 1. Data Quality Validation

Performed:

- Missing-value analysis
- Duplicate analysis
- Datetime validation
- Negative-duration investigation
- Extreme-duration analysis
- Trip-distance validation
- Fare validation
- Negative-fare investigation
- Extreme-fare investigation
- Passenger-count validation
- Location-ID validation
- Date-range validation
- Financial anomaly detection

### 2. Feature Engineering

Created analytical features including:

- Pickup date
- Pickup hour
- Weekday
- Weekend flag
- Time-of-day
- Peak period
- Trip duration
- Speed
- Distance category
- Revenue per mile
- Revenue per minute

### 3. Business Performance Analysis

Analyzed:

- Overall revenue
- Trip volume
- Average fare
- Average distance
- Average duration
- Tips
- Passenger count

### 4. Time Analysis

Performed:

- Daily trend analysis
- Hourly demand analysis
- Weekday analysis
- Weekend vs weekday comparison
- Peak vs off-peak analysis
- Hour × weekday analysis
- Revenue anomaly investigation

### 5. Advanced Analysis

Performed:

- Distance analysis
- Distance × speed analysis
- Distance × revenue efficiency
- Payment analysis
- Passenger analysis
- Pickup-location analysis

---

## 🛠️ Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Datetime Analysis
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Time-Series Analysis
- Revenue Analysis
- Anomaly Detection
- Segmentation
- Business Analysis

---

## 📈 Results & Business Recommendations

### Key Results

The analysis identified:

- **3,472,949 total trips**
- Approximately **$88.87M total revenue**
- Average revenue per trip: **$25.59**
- Median revenue per trip: **$19.95**
- Average fare: **$17.06**
- Average trip distance: **3.09 miles**
- Median trip distance: **1.67 miles**
- Average trip duration: **14.63 minutes**
- Median trip duration: **11.7 minutes**
- Total tips: approximately **$10.28M**
- Average tip: approximately **$2.96**
- Average passengers: approximately **1.30**

### Demand Findings

**1. Evening is the highest-volume period**

The **6 PM hour** records approximately **267,817 trips**, making it the highest-volume hour in the analysis.

The 5 PM and 7 PM periods also show high trip volumes.

**2. Weekdays generate more revenue than weekends**

Weekday trips:

- **2.59M trips**
- Approximately **$67.35M revenue**
- Average revenue/trip: **$25.96**

Weekend trips:

- **878K trips**
- Approximately **$21.51M revenue**
- Average revenue/trip: **$24.49**

**3. Thursday has the highest total revenue among weekdays**

Thursday generates approximately **$15.84M** in revenue with approximately **613,845 trips**.

**4. Evening Peak**

Evening Peak:

- Approximately **959K trips**
- Approximately **$24.71M revenue**
- Average revenue/trip: **$25.76**

**5. January 20 anomaly**

January 20 recorded:

- **90,048 trips**
- Approximately **$3.28M revenue**
- Average revenue/trip: **$36.47**
- Average fare: **$27.95**

The unusually high revenue per trip compared with other Mondays was investigated as a potential anomaly rather than treated as a normal demand pattern.

### Business Recommendations

**1. Optimize Fleet Availability Around High-Demand Hours**

The 5 PM–7 PM period shows particularly high trip volume. Fleet allocation can be aligned with these demand patterns.

**2. Use Weekday Demand for Driver Planning**

Weekdays generate significantly more total trips and revenue than weekends. Driver availability can therefore be planned using weekday-specific demand patterns.

**3. Focus on High-Value Time Windows**

Some hours have lower trip volumes but higher average revenue per trip. Fleet planning should consider both **trip volume and revenue efficiency**, rather than volume alone.

**4. Monitor Revenue Anomalies**

January 20 shows unusually high revenue per trip. Similar anomalies should be automatically flagged for investigation rather than being directly interpreted as a sustainable business trend.

**5. Use Location-Level Demand for Fleet Allocation**

Pickup-location analysis can be used to identify high-demand areas and improve vehicle positioning during high-demand periods.

---

# 🧰 Common Technology Stack

| Area | Tools |
|---|---|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistics | SciPy |
| Environment | Jupyter Notebook |
| Analysis | EDA, Segmentation, Statistical Analysis |
| Business | KPI Analysis, Trend Analysis, Business Recommendations |

---

# 📊 Overall Data Analysis Workflow

```text
Raw Dataset
     ↓
Data Profiling
     ↓
Data Cleaning
     ↓
Data Validation
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Business Analysis
     ↓
Visualization
     ↓
Key Insights
     ↓
Business Recommendations
```

---

# 👤 Author

**Vishvash Kumar**

Aspiring Data Analyst

**Skills:** Python | SQL | Excel | Power BI | Data Analysis

GitHub: **@vishvashvk-cmyk**

---

## 📜 License

This repository is open-source and available under the MIT License.
