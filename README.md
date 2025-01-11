# E-commerce Data Analysis  

## 📖 Project Overview  
This project analyzes e-commerce transaction data to understand customer purchasing behavior and provide actionable insights for targeted marketing. By utilizing **RFM (Recency, Frequency, Monetary)** analysis, clustering, and data visualization techniques, the project segments customers into meaningful groups, enabling data-driven marketing strategies to improve customer retention and revenue.  

---

## 🚀 Key Features  
### 1. **Data Preparation**  
- Dataset: E-commerce dataset from Kaggle.  
- Cleaned data by handling duplicates, missing values, and adding new features like `TotalPrice`.  

### 2. **RFM Analysis**  
- **Recency**: Time since the last purchase.  
- **Frequency**: Total unique transactions.  
- **Monetary**: Total spending.  
- Scored customers based on quartiles to create an RFM profile.  

### 3. **Customer Segmentation**  
- Applied **K-Means Clustering** to segment customers into four groups:  
  - **Champions**: High-value and frequent customers.  
  - **Loyal Customers**: Consistent buyers with moderate spending.  
  - **At-Risk Customers**: Previously active but now disengaged.  
  - **Hibernating Customers**: Rarely active with low spending.  
- Used the **Elbow Method** to identify the optimal number of clusters.  

### 4. **Visualizations**  
- Distribution analysis of recency, frequency, and monetary values.  
- Clustering scatter plots (e.g., Recency vs. Frequency, Frequency vs. Monetary).  
- Pie charts to display the proportion of customers in each cluster.  
- 3D scatter plots for better cluster interpretation.  

### 5. **Insights & Recommendations**  
- Identified high-value customers (Champions) for loyalty programs.  
- Recommended strategies for re-engaging inactive or at-risk customers.  
- Suggested marketing plans tailored to each segment’s purchasing behavior.  

---

## 🔑 Key Insights  
- **Champions (Cluster 2)**: High spending, frequent buyers with recent activity. Ideal for loyalty rewards and exclusive promotions.  
- **Loyal Customers (Cluster 0)**: Consistent buyers who can be targeted with cross-selling and referral incentives.  
- **At-Risk Customers (Cluster 3)**: Previously active customers needing re-engagement campaigns.  
- **Hibernating Customers (Cluster 1)**: Low activity and spending; require targeted ads and special discounts to regain interest.  

---

## 🛠️ Technologies Used  
- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **Tools**: Jupyter Notebook  
- **Techniques**: RFM Analysis, K-Means Clustering, Data Visualization  

---

## 📊 Visualizations  
1. **Cluster Distribution**: Pie charts and bar plots to display customer segments.  
2. **Recency vs. Frequency**: Highlights engagement levels and purchasing trends.  
3. **Monetary Contributions by Cluster**: Identifies high-value groups for prioritization.  
4. **3D Cluster Visualization**: Better understanding of customer behavior across multiple dimensions.  

---

## 💡 Marketing Recommendations  
- **Champions**: Reward loyalty with exclusive offers and early access to new products.  
- **Loyal Customers**: Upsell with personalized recommendations and volume discounts.  
- **At-Risk Customers**: Engage with surveys, discounts, and targeted communication to reignite interest.  
- **Hibernating Customers**: Use retargeting ads and bundled deals to encourage purchases.  

---

## 📈 Conclusion  
This project highlights the effectiveness of RFM segmentation and clustering in understanding customer behavior. The insights derived enable businesses to personalize marketing strategies, improve customer retention, and maximize revenue.  

---

**Author**: Sushmitha Sudharsan  
Feel free to explore, contribute, or provide feedback!
