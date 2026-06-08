# E-Commerce-Analytics
Data-Driven E-Commerce Analytics: Customer Behavior, Delivery Optimization, and Revenue Insights
# Data-Driven E-Commerce Analytics: Customer Behavior, Delivery Optimization, and Revenue Insights

An advanced business analytics project completed during an industry internship with **Cognifyz Technologies** as part of an MBA program in Business Analytics at **Anna University Regional Campus, Coimbatore**.

## 📊 Project Overview
This project focuses on transforming raw transactional and operational logistics data from e-commerce delivery platforms into actionable business intelligence. By combining **Descriptive, Diagnostic, and Predictive Analytics**, this study identifies core operational bottlenecks, maps customer satisfaction dynamics, segments purchasing behavior, and builds an early-warning system for delivery delays.

### 🎯 Key Objectives
* **Demand Pattern Mapping:** Identify peak ordering periods and high-demand windows to optimize supply chain readiness.
* **Logistics Efficiency Evaluation:** Track delivery timelines and isolate root variables causing operational delays.
* **Customer Experience Analytics:** Analyze customer sentiment via service ratings and uncover hidden correlations with transaction sizes.
* **Strategic Revenue Analysis:** Evaluate macro revenue streams across key product verticals to recommend high-yield inventory allocations.
* **Advanced Modeling:** Deploy unsupervised machine learning for strategic customer segmentation and supervised learning to forecast delivery risks.

---

## 🛠️ Tech Stack & Analytical Ecosystem
* **Core Language:** Python
* **Data Wrangling & Processing:** Pandas, NumPy
* **Statistical Computing & Outlier Detection:** SciPy (Z-score analysis)
* **Data Visualization & Exploratory Analytics:** Matplotlib, Seaborn
* **Machine Learning Pipelines:** Scikit-learn
* **Business Intelligence Dashboards:** Power BI

---

## 🔬 Core Analytical Framework & Methodology

### 1. Exploratory Data Analysis (EDA) & Diagnostics
* **Univariate & Bivariate Distribution:** Investigated individual distributions of delivery times, order sizes, and feedback metrics.
* **Correlation Heatmaps:** Evaluated multidimensional linear relationships between order ticket value, absolute delivery durations, and customer satisfaction scores.
* **Outlier Detection:** Implemented $Z\text{-score}$ filtering ($|Z| > 3$) on processing metrics to isolate anomalous systemic delays.

### 2. Customer Segmentation (Unsupervised Learning)
* Applied **K-Means Clustering** to divide the consumer base into distinct tactical profiles based on transactional values and service satisfaction. This enables hyper-personalized targeted marketing and retention strategies.

### 3. Predictive Modeling (Supervised Learning)
* Built a **Logistic Regression Pipeline** trained on operational and category metrics to predict high-probability delivery delays before they manifest in real-time supply chain queues.

---

## 📈 Strategic Business Insights & Findings

* **The Mid-Day Demand Peak:** Order velocity sharply concentrates between **11:00 AM and 3:00 PM**, driven by lunch-hour demand patterns, peaking heavily around **1:00 PM**.
* **Logistics Consistency:** Standard operations successfully constrain the majority of package drops to a **40-60 minute window**. Delayed orders experience significant variance, indicating systemic friction during peak constraints.
* **Value-Satisfaction Link:** A strong positive trend indicates that higher transaction values closely correlate with top-tier feedback scores ($4\text{-}5 \text{ stars}$), highlighting the critical importance of prioritizing premium accounts.
* **Concentrated Revenue Streams:** Macro revenue generation depends heavily on a select few dominant categories—specifically **Personal Care** ($29\%$) and **Grocery** ($24.3\%$).

---

## 💡 Data-Driven Recommendations

### System Optimization
* **Dynamic Peak Staffing:** Shift operational human resource allocation and expand delivery partner density within the high-volume **11 AM – 3 PM** window to mitigate late drop-offs.
* **Predictive Dispatching:** Integrate the Logistic Regression delay-risk model directly into the logistical dispatch queue to flag high-risk orders preemptively.
* **Inventory Balance:** Optimize supply chain stocks toward top-performing pillars (Personal Care and Groceries) while diversifying or running targeted promotions in trailing product lines like Snacks.

### Customer Engagement
* **VIP Workflows:** Build specialized loyalty tracks and prioritized shipping lanes for high-value customer clusters.
* **Feedback Diagnostic Loop:** Set up automated text-mining alerts for low service ratings ($1\text{-}2 \text{ stars}$) to trigger immediate customer support interventions.

---

## 📂 Repository Structure
```text
├── Data/
│   └── Ecommerce_Delivery_Analytics_New.csv # Project secondary dataset
├── Notebooks/
│   └── ecommerce_analytics_pipeline.ipynb   # Complete data cleaning, EDA, & ML models
├── Dashboards/
│   └── Ecom_Delivery_Insights.pbix          # Interactive Power BI workspace file
├── Reports/
│   └── 710024633029_Sugil_R_Project.pdf     # Formal academic project documentation
└── README.md                                # Executive summary and repo layout
