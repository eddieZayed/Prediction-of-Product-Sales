# Prediction-of-Product-Sales

This project explores a retail sales dataset to understand what factors affect product sales across different outlets.
The goal is to perform exploratory data analysis (EDA) and build a machine learning model to predict `Item_Outlet_Sales`.
### 1) Distribution of Item Outlet Sales (Histogram)
<img width="580" height="455" alt="Distribution of Item Outlet Sales" src="https://github.com/user-attachments/assets/d6609ae1-b15d-48ac-859c-634d275827f2" />

**Insight:** Most products generate low to moderate sales, while only a small number of products achieve very high sales.

---

### 2) Boxplot of Item Outlet Sales
<img width="589" height="416" alt="Boxplot of Item Outlet Sales" src="https://github.com/user-attachments/assets/b6de29fe-84ad-4935-bb80-a763eced1bb5" />

**Insight:** The boxplot shows that most products have low to moderate sales, with a median around 1900. Sales values are right-skewed, and a small number of products achieve very high sales, appearing as outliers.

---

### 3) Correlation Heatmap of Numeric Features
<img width="686" height="589" alt="corr_heatmap" src="https://github.com/user-attachments/assets/94580620-3ed2-4cdd-98e7-9a58a1ebfb6a" />

**Insight:** Item_MRP has the strongest positive correlation with Item_Outlet_Sales, indicating that higher-priced items tend to generate higher sales, while other numeric features show weak relationships.

---

### 4) Count of Products by Item Type
<img width="580" height="590" alt="Count of Products by Item Type Plot" src="https://github.com/user-attachments/assets/64abe48b-1cff-4ada-a94a-55fcd1d4666d" />

**Insight:** Fruits and Vegetables and Snack Foods are the most common product types in the dataset, while Seafood and Breakfast appear least frequently.

---

### 5) Average Sales by Item Type
<img width="1014" height="649" alt="Average Sales by Item Type" src="https://github.com/user-attachments/assets/f8cc9722-e0ae-4f24-a2ee-afd557bc5c89" />

**Insight:**  
Although some item types have slightly higher average sales than others, the differences between most categories are relatively small, indicating that average sales are fairly consistent across product types.

---

### 6) Relationship Between Item MRP and Item Outlet Sales
<img width="589" height="455" alt="Relationship between Item MRP and Item Outlet Sales" src="https://github.com/user-attachments/assets/de8bc54f-9ae8-4c56-96d5-6488008bc6a4" />

**Insight:**  
The scatter plot shows a strong positive relationship between item price (Item_MRP) and item outlet sales, indicating that higher-priced items generally generate higher sales.

---

### 7) Average Sales by Outlet Type
<img width="580" height="511" alt="Average Sales by Outlet Type Barplot" src="https://github.com/user-attachments/assets/49f1c738-4f67-484b-beeb-263840b252d3" />

**Insight:**  
The bar plot shows that supermarket outlets generate significantly higher average sales than grocery stores, indicating that outlet type plays an important role in sales performance.

---

### 8) Average Sales by Outlet Size
<img width="589" height="455" alt="Average Sales by Outlet Size Boxplot" src="https://github.com/user-attachments/assets/72e47aa5-59c3-4c03-b894-7d0d52363e28" />

**Insight:**  
The boxplot shows that medium and high-sized outlets tend to have higher sales distributions than small outlets. Across all outlet sizes, sales are right-skewed with several high-value outliers.


