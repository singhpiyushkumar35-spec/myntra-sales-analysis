# Myntra Dataset Overview

## Dataset Summary

The Excel workbook contains **5 sheets**:

| Sheet Name | Description | Rows | Columns |
|------------|-------------|------|---------|
| Data | Raw product data | 21,605 | 18 |
| Clean data | Processed and cleaned dataset | 11,438 | 15 |
| KPI analysis | Summary KPI calculations | 13 | 9 |
| Pivot table | Aggregated analysis tables | 34 | 16 |
| Charts | Data prepared for visualizations | 16 | 19 |

---

# Clean Data Snapshot

The cleaned dataset contains **11,438 products** across **245 product categories** and **1,458 brands**.

## Key Columns

- Product Name
- Brand Name
- Rating
- Rating Count
- Marked Price
- Discounted Price
- Product Category
- Product Description
- Revenue
- Discount Percentage

---

# Key Metrics

| Metric | Value |
|----------|----------|
| Total Products | 11,438 |
| Total Categories | 245 |
| Total Brands | 1,458 |
| Average Rating | 4.16 / 5 |
| Average Marked Price | ₹2,288.84 |
| Average Discounted Price | ₹1,208.51 |
| Average Discount | 43.97% |

---

# Pricing Statistics

| Metric | Marked Price (₹) | Discounted Price (₹) |
|----------|----------|----------|
| Minimum | 55 | 49 |
| 25th Percentile | 1,199 | 599 |
| Median | 1,899 | 874 |
| 75th Percentile | 2,799 | 1,399 |
| Maximum | 33,900 | 33,900 |

---

# Most Popular Product Categories (by Product Count)

| Category | Products |
|----------|----------|
| tshirts | 1,121 |
| dresses | 710 |
| shirts | 650 |
| tops | 616 |
| kurta-sets | 590 |
| kurtas | 510 |
| jeans | 422 |
| handbags | 380 |
| casual-shoes | 346 |
| trousers | 311 |

---

# Top Revenue-Generating Categories

| Category | Revenue |
|----------|----------:|
| perfume-and-body-mist | ₹159,544,098 |
| kurta-sets | ₹62,605,175 |
| dresses | ₹55,142,174 |
| watches | ₹49,477,916 |
| tshirts | ₹48,325,559 |
| kurtas | ₹48,111,928 |
| shirts | ₹42,204,249 |
| handbags | ₹37,076,553 |
| tops | ₹36,775,766 |
| hair-appliance | ₹36,370,429 |

---

# Top Revenue-Generating Brands

| Brand | Revenue |
|--------|---------:|
| JAGUAR | ₹96,503,294 |
| Roadster | ₹59,111,098 |
| Plum | ₹56,575,241 |
| DressBerry | ₹48,535,395 |
| MCaffeine | ₹38,870,147 |
| Philips | ₹34,331,989 |
| Lakme | ₹32,333,287 |
| HRX by Hrithik Roshan | ₹30,789,294 |
| Maybelline | ₹21,911,781 |
| Vishudh | ₹20,393,983 |

---

# Key Insights

1. **Apparel dominates product volume**, with T-shirts, Dresses, Shirts, and Tops accounting for a large portion of listings.
2. **Beauty and Personal Care products** (Perfume & Body Mist) generate the highest revenue despite not having the highest product count.
3. The dataset shows an **average discount of nearly 44%**, indicating aggressive promotional pricing.
4. Product ratings are generally strong, with an **average rating of 4.16**.
5. Revenue is highly concentrated among a few brands, with **JAGUAR** generating almost ₹96.5 million in revenue.
6. Premium products exist in the catalog, with prices reaching **₹33,900**.

---

# Data Quality Notes

- The raw sheet contains some unnamed columns and duplicate brand columns.
- The cleaned sheet appears suitable for analysis and dashboarding.
- Revenue and discount calculations have already been derived in the cleaned dataset.
- Product categories are highly granular (245 unique categories), enabling detailed segmentation analysis.
