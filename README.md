# Airbnb EDA: What makes a listing popular?
## Overview
> This exploratory data analysis examines Airbnb listings and the features they include to uncover which factors drive guest engagement and high performance.  
>  
> To define what makes a listing "popular," we used two main metrics: the **number of reviews** and the **overall review score**.  
>  
> This analysis helps **hosts create listings that better cater to guest needs and satisfaction**, ultimately improving their visibility, performance, and alignment with Airbnb’s mission: *“to create a world where anyone can belong anywhere.”*

# Tools 
- Python (Jupyter Notebook)
- Pandas, Numpy, Seaborn, Matplotlib, scikit-learn
- Tableau (Dashboard)

## 🧹 Data Transformation

To prepare the Airbnb listings dataset for analysis, the following steps were taken:

1. **Removed Outliers**  
   - Filtered out extreme values in price, number of reviews, and other numeric fields to reduce skew and improve analysis reliability.

2. **Dropped Irrelevant Columns**  
   - Removed columns that did not contribute meaningful insights (e.g. URLs, host names).

3. **Handled Missing Values**  
   - Filled or removed nulls depending on context and column importance (e.g. dropped rows with missing critical fields like price or review scores).

4. **Feature Engineered a Popularity Score**  
   - Created a new metric combining number of reviews and review score to quantify listing popularity.

5. **Filtered for Active Listings**  
   - Removed listings with very few reviews to focus on more established and relevant listings.

6. **Data Type Conversions**  
   - Converted columns like boolean and strings(e.g prices, percentages) to the appropriate types for analysis.
## Exploratory Data Analysis & Key Findings
Analysis was centered on the features of Airbnb listings and what features made a impact of a listings popularity score

- Price alone is not the sole factor: **affordability combined with quality features leads to better performance**

