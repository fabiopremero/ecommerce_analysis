# E-commerce Sales Analysis

This project explores and analyzes an **E-commerce dataset** using Python and Power BI. The primary goals were to understand revenue trends, seasonality, product performance, and user behavior across multiple years.

---

## Datasets

The dataset was sourced from [Kaggle - E-commerce A/B Testing 2022 Dataset](https://www.kaggle.com/datasets/putdejudomthai/ecommerce-ab-testing-2022-dataset1/data).

### Key Tables:
- **Fact Table:** Transactional sales data (includes `total_price`, `date`, `product_id`, `payment_type`).
- **Date Table:** Calendar mapping with `year`, `month`, `date`.
- **Product Table:** Product details (optional for product names).

---

## Analysis Performed

### Time-Based Revenue Trends
- Built **monthly and annual revenue trends**.
- Identified that **2014 had incomplete data** (started from March).
- Removed specific months: January and February 2014, and January 2021 for data consistency.
- Observed that **annual revenue from 2015 to 2020 was stable**, with no significant year-over-year growth.

---

### Seasonality & Revenue Patterns
- Prepared the dataset to visualize monthly and yearly revenue.
- Created a **bar chart separated by year** to understand overall performance.
- Determined that **year-over-year changes were minimal**, indicating a mature and stable revenue stream.

---

### Product-Level Analysis
- Identified the **Top 10 Products by Total Revenue** using Python.
- Next steps:
   - Analyze **Products with Declining Sales** over time.
   - Explore **Payment Type Distribution** to understand customer preferences.

---

## Tools Used
- **Python:** Data cleaning, grouping, and visualization.
- **Power Query (Power BI):** Data preparation, text extraction, custom columns.
- **Seaborn & Matplotlib:** Visualizations in Python.

---

## Next Steps (with time)
- Analyze **Products with Declining Sales**.
- Explore **Payment Type Distribution** (if available in the dataset).
- Build additional Power BI dashboards to enhance visual storytelling.

---