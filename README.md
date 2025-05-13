# ✈Travel Customer Segmentation for Reward Optimization

**Customer Clustering & Persona-Driven Reward Strategies for Travel Platform Optimization**

## Author

Victoria Finch 2025

- 📄 [Detailed Report (PDF)]([https://your-link.com/executive-summary](https://docs.google.com/document/d/14zDn9gSJEaXqdtxEoHi9f_URR1TZdAxVFRGNsDLSoeM/edit?usp=sharing))

---

## Project Description

This project applies unsupervised machine learning techniques (clustering) to identify distinct user groups in a travel booking platform. These insights empower targeted reward strategies through email marketing campaigns, aiming to improve customer retention, increase conversions, and maximize customer lifetime value.

The output includes six customer clusters, each with a unique profile, behaviors, and engagement patterns. Recommendations and email reward strategies are tailored to each persona for optimal marketing alignment.

---

## Project Goals

- Understand user segmentation through clustering.
- Develop targeted reward strategies for each segment.
- Provide actionable insights to marketing stakeholders.

##  Results & Analysis

### 📊 Summary of Results

The clustering analysis produced **6 distinct customer segments**, each representing a meaningful behavioral profile for targeted marketing. Here’s a breakdown of the key clusters and associated insights:

| Cluster | Name                    | Booking Rate | Avg. Trip Price | Key Traits                              |
|--------:|-------------------------|---------------|------------------|------------------------------------------|
| 0       | VIP / High Value Users  | 99.6%         | $4,140           | High spend, family travel, premium perks |
| 1       | Mass-Market Travelers   | 99.2%         | $909             | Budget-minded, domestic travel, bundle deals |
| 2       | Power Family Travelers  | 98.5%         | $1,080           | Multi-room bookings, family-oriented     |
| 3       | Impulse Browsers        | 93.7%         | $876             | Spontaneous, mobile-first, low loyalty   |
| 4       | Dormant Users           | 0.0%          | $0               | Inactive, churned users, re-engagement needed |
| 5       | Cancellation Users      | N/A           | $1,981           | High cancellation rate, unpredictable     |

---

### Key Metrics

- **Session-to-Trip Ratio**: Used to assess user engagement before booking.
- **Avg. Trip Price**: Indicates user value potential and segment worth.
- **Persona Tags**: Categorical features like `is_family`, `is_impulse_traveler`, and `has_children` informed behavioral modeling.
- **Booking Behavior**: Click depth, session length, and discount usage were considered.

---

###  Process Overview

1. **Data Preprocessing**  
   - Cleaned and standardized user behavioral and transactional data.
   - Feature engineering on user traits (e.g., trip frequency, discount usage).
   - Handled missing values and encoded categorical features.

2. **Clustering Algorithm**
   - Employed **KMeans Clustering** with normalization.
   - Optimal cluster count was determined using the **elbow method** and **silhouette score**.
   - Labeling and interpretation of clusters based on descriptive statistics and persona mapping.

3. **Post-Processing**
   - Cluster assignments were appended to user-level data.
   - Generated cluster profiles and corresponding user personas.
   - Linked insights to marketing strategies and reward systems.

---

###  Tools & Technologies

- **Python**: Core language used for analysis.
- **pandas / numpy**: Data wrangling and feature generation.
- **scikit-learn**: KMeans clustering and model evaluation.
- **matplotlib / seaborn**: Visualizations and EDA plots.
- **Jupyter Notebooks**: Interactive analysis and prototyping.
- **Tableau Public**: Dashboards for cluster insights.
- **Google Slides**: Final presentation for stakeholders.
- **Google Sheets**: Shared cluster metrics and strategy mapping.

---

