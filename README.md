# 🍔 Food Delivery Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing food delivery operations to understand delivery performance, identify delay patterns, compare restaurant efficiency, and explore the relationship between traffic conditions and delivery times.

Using Python-based data analysis and visualization techniques, I transformed raw delivery data into meaningful business insights to support data-driven decision-making.

## 🎯 Business Objectives

- Analyze on-time and delayed order distribution.
- Compare average delivery times across restaurants.
- Identify restaurants with the highest number of delayed orders.
- Investigate delivery performance across different traffic levels.
- Examine numerical variables such as order value, delivery distance, preparation time, and customer ratings for potential outliers.
- Recommend operational improvements based on the findings.

## 🛠️ Tools & Technologies

- **Python** — Data analysis
- **Pandas** — Data manipulation, filtering, grouping, and aggregation
- **Matplotlib** — Data visualization and comparative charts
- **Seaborn** — Statistical data visualization
- **Jupyter Notebook** — Interactive analysis and documentation

## 📊 Key Business Insights

### 1. Order Delivery Performance
- Total orders analyzed: **1,000**
- On-time orders: **678 (67.8%)**
- Delayed orders: **322 (32.2%)**

**Insight:** Approximately one-third of orders experienced delays, indicating an opportunity to improve delivery reliability.

### 2. Delivery Time by Traffic Level
- High traffic: approximately **61 minutes**
- Medium traffic: approximately **55 minutes**
- Low traffic: approximately **51 minutes**

**Insight:** Average delivery time was highest during high-traffic conditions, suggesting that traffic management may be an important factor in delivery performance.

### 3. Restaurant-Wise Delivery Performance
- Curry Corner recorded the lowest average delivery time at approximately **52.28 minutes**.
- Dosa Palace recorded the highest average delivery time at approximately **58.62 minutes**.

**Insight:** Comparing restaurant workflows may help identify opportunities to improve preparation, dispatch, and delivery coordination.

### 4. Delayed Order Analysis
- Pizza Point had the highest number of delayed orders, with **41**.
- Dosa Palace recorded **39** delayed orders.
- Biryani Express and Green Bowl recorded **36** delayed orders each.

**Insight:** These restaurants should be investigated further, taking total order volume into account before comparing their performance.

### 5. Delay Rate by Traffic Level
- High traffic: **46.99%**
- Medium traffic: **32.20%**
- Low traffic: **22.22%**

**Insight:** The observed delay rate was substantially higher during high traffic than during low traffic. This is an association in the dataset and does not, by itself, establish causation.

## 📈 Data Analysis Techniques

- Data inspection and preprocessing
- Outlier identification
- `groupby()` and aggregation
- `value_counts()` and normalized percentages
- Filtering records using conditions
- Restaurant-wise performance comparison
- Bar charts and statistical visualizations
- Business insight generation

## 💡 Business Recommendations

1. **Improve peak-hour planning:** Review delivery partner allocation and route planning during high-traffic periods.
2. **Optimize restaurant workflows:** Investigate preparation and dispatch processes at restaurants with longer delivery times.
3. **Monitor delivery KPIs:** Track on-time delivery percentage, average delivery time, and delay rate.
4. **Compare delay rates fairly:** Evaluate delayed orders as a percentage of each restaurant's total orders.
5. **Improve customer experience:** Investigate whether delivery delays are associated with lower customer ratings.

## 📂 Project Structure

```text
Food-Delivery-Data-Analysis/
│
├── project.ipynb       # Data analysis and visualizations
├── dataset.csv         # Source dataset (if permitted to share)
└── README.md           # Project documentation
```



## 📌 Conclusion

This project demonstrates how Python-based exploratory data analysis can help evaluate food delivery operations and identify potential areas for improvement. The analysis highlights delivery delays, differences in restaurant delivery times, and variations across traffic conditions.

The findings can support further investigation into operational efficiency, delivery planning, and customer satisfaction.

## 👨‍💻 Skills Demonstrated

`Python` · `Pandas` · `Matplotlib` · `Seaborn` · `Exploratory Data Analysis` · `Data Visualization` · `Business Insights` · `Data-Driven Decision Making`
