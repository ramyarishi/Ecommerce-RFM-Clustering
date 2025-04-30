# 🛍️ Customer Segmentation using RFM Analysis and Clustering

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis followed by clustering techniques. The goal is to identify valuable customer groups to enhance marketing strategies and improve customer retention.

---

## 📌 About  
This project uses RFM analysis to evaluate customer behavior based on how recently and frequently they purchase, and how much they spend. By applying clustering algorithms such as K-Means or Hierarchical Clustering, the project segments customers into meaningful groups for targeted marketing and decision-making.

---

## 🗂️ Dataset  
The dataset contains customer transaction data, including:
- Invoice date
- Customer ID
- Purchase quantity
- Unit price
- Country

> Typically sourced from e-commerce or retail platforms.

---

## 🔍 RFM Analysis  
- **Recency**: Days since last purchase  
- **Frequency**: Number of purchases  
- **Monetary**: Total amount spent  

These metrics are computed for each customer and used as input features for clustering.

---

## 🧪 Clustering Methods  
- K-Means Clustering  
- Elbow Method for optimal k  
- Silhouette Score for validation  
- (Optional) Hierarchical Clustering  

---

## 📈 Tech Stack  
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

---

## 📊 Results  
Customers are grouped into clusters such as:
- High Value
- Frequent Buyers
- Recent Inactive
- Low Value

This segmentation allows businesses to customize promotions and retain high-value customers effectively.




