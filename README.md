 📊 Amazon Electronics Sales Analysis

## Project Overview

This project analyzes Amazon Electronics reviews data (1.2M+ records) to uncover:

* Revenue and rating trends over time
* Customer segments based on engagement and rating behavior
* Product performance across categories and brands
* Insights for data-driven business decisions

The project combines Exploratory Data Analysis (EDA), Customer Segmentation, and Visualization to demonstrate practical Data Analytics skills.

---

## Tech Stack

* Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* Environment: Jupyter Notebook

---

 Key Analysis Steps

1. Data Cleaning & Preprocessing

   * Handled missing values (brands, user attributes)
   * Extracted temporal features (year, month, date)
   * Standardized numerical features

2. Exploratory Data Analysis (EDA)

   * Distribution of ratings
   * Top categories and brands
   * Yearly and monthly trends in reviews

3. Customer Segmentation (K-Means Clustering)

   * Features: number of reviews, average rating, variability, active years
   * Optimal number of clusters: 6 (Silhouette Score: 0.82)
   * Segments identified: Loyal Fans, Silent Buyers, Critical Reviewers, Casual Positives, New Users, Mixed Raters

4. Visualization

   * Histograms, bar plots, time-series plots
   * Cluster scatter plots (n\_reviews\_log vs avg\_rating)
   * Boxplots to compare rating behaviors across clusters

---

Business Insights

* Loyal Fans provide consistent high ratings and should be nurtured for brand advocacy.
* Critical Reviewers leave many low ratings → monitor for quality issues.
* Silent Buyers can be targeted with engagement campaigns to increase reviews.
* New Users need onboarding and personalized recommendations to retain them.

---

Next Steps

* Build a Recommendation System (Collaborative Filtering / SVD)
* Create an interactive dashboard in Tableau or Power BI
* Deploy as a data portfolio project on GitHub
