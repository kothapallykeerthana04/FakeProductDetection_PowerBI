# FakeProductDetection_PowerBI

# 🛍️ Fake Product Detection in Online Marketplaces

## 📌 Project Overview
This Power BI project analyzes customer reviews to detect patterns in **fake vs. real product reviews**. It focuses on identifying categories with the highest fake reviews, distribution of ratings, and helps businesses flag potential fraudulent activity.

---

## 📂 Folder Structure

FakeProductDetection/
├── data/
│ └── fake_reviews.csv
├── dashboard/
│ └── FakeProductDashboard.pbix
├── reports/
│ └── FakeProductReport.pdf
├── README.md

---

## 📊 Key Metrics & Visuals

- **Fake Review %** (KPI Card)
- **Total Reviews** (KPI Card)
- **Fake vs Real Reviews by Category** (Clustered Column Chart)
- **Ratings vs IsFakeReview** (Stacked Chart)
- **Slicers for Interactivity**
  - `Category`
  - `IsFakeReview`
  - `Rating`

---

## 🔍 Dataset Overview

- **Source**: Simulated or publicly available Amazon review dataset
- **Fields Used**:
  - `review_text`
  - `rating`
  - `product_category`
  - `IsFakeReview` (0 = Real, 1 = Fake)

---

## 📈 Tools Used

- **Power BI Desktop** – Visualizations and dashboards
- **DAX** – Calculated fields (e.g., `FakePercent`)
- **CSV Format** – For dataset compatibility

---

## 💡 Key Insights

- Most fake reviews are rated 5-stars
- Certain product categories (like Electronics and Accessories) show higher fake review density
- Over X% of the total reviews were flagged as fake

---

## ✅ Recommendations

- Implement filters for 5-star review anomalies
- Prioritize human moderation in fake-prone categories
- Promote verified purchase reviews to increase trust

---

## 🚀 Future Improvements

- Add time-based trends (date of review)
- Include seller info to detect seller-specific fraud
- Use Python ML model to classify reviews as fake/real, then visualize predictions in Power BI

---

## 📄 Report & Dashboard Access

- 📊 **Dashboard**: [`FakeProductDashboard.pbix`](./dashboard/FakeProductDashboard.pbix)
- 📑 **PDF Report**: [`FakeProductReport.pdf`](./reports/FakeProductReport.pdf)

---

## ✍️ Author

- **Name**: Kothapally Keerthana
- **LinkedIn**: https://www.linkedin.com/in/kothapally-keerthana0402/
---

