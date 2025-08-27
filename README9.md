# 🛒 Customer Segmentation using Clustering

## 📌 Project Overview
This project demonstrates **Customer Segmentation** using **unsupervised machine learning techniques**.  
The goal is to cluster customers based on their shopping behavior and spending habits, enabling businesses to design **personalized marketing strategies** for different customer groups.

We use **K-Means Clustering, PCA, and t-SNE** to identify meaningful customer segments from raw shopping data.

---

## 🎯 Objectives
- Import and preprocess customer shopping data  
- Perform **Exploratory Data Analysis (EDA)**  
- Scale features using **StandardScaler**  
- Apply **K-Means clustering** for customer segmentation  
- Reduce dimensionality using **PCA** and visualize clusters  
- Apply **t-SNE** for advanced visualization  
- Evaluate cluster quality using **Silhouette Score**  
- Provide insights for **marketing strategies**  

---

## 📂 Dataset
The dataset used is:
```
customer_shopping_data.csv
```

### Dataset Preview
- Shape: `(rows, columns)` → Shown after loading  
- Sample columns:
  - Customer ID  
  - Gender  
  - Age  
  - Category  
  - Quantity  
  - Price  
  - Total Amount  

---

## ⚙️ Tech Stack
- **Python 3.x**
- **Libraries:**
  - `pandas` → Data manipulation  
  - `numpy` → Numerical operations  
  - `matplotlib` → Data visualization  
  - `scikit-learn` → Clustering, scaling, evaluation 

---

## 🛠️ Project Workflow

### 1. Import Libraries
All required libraries for data handling, clustering, and visualization are imported.

### 2. Load Dataset
```python
df = pd.read_csv("customer_shopping_data.csv")
```

### 3. Exploratory Data Analysis (EDA)
- Shape of dataset  
- Null/missing values  
- Data types and distributions  
- Basic statistics  

### 4. Feature Scaling
- Standardize numerical features using **StandardScaler**.

### 5. K-Means Clustering
- Apply **Elbow Method** to determine optimal number of clusters  
- Fit **KMeans** model  
- Assign cluster labels to customers  

### 6. Dimensionality Reduction
- **PCA** → Reduce features to 2D/3D for visualization  
- **t-SNE** → High-quality visualization of customer clusters  

### 7. Evaluation
- Compute **Silhouette Score** to validate cluster performance  

### 8. Visualization
- Plot **clustered customers** with PCA and t-SNE  
- Distribution of customers across clusters  

### 9. Insights
- Analyze characteristics of each cluster  
- Suggest **marketing strategies** based on segment behavior  

---

## 📊 Results & Insights
- Customers are grouped into meaningful clusters (e.g., **High Spenders, Budget Shoppers, Medium Buyers**)  
- Each cluster shows unique patterns in **spending behavior, purchase frequency, and demographics**  
- Businesses can:
  - Offer **discounts** to price-sensitive clusters  
  - Promote **premium products** to high-value clusters  
  - Provide **loyalty programs** for frequent buyers  

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-clustering.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Segmentation_Clustering.ipynb
   ```

---

## 📌 Future Improvements
- Try **DBSCAN / Hierarchical Clustering**  
- Include **RFM Analysis (Recency, Frequency, Monetary)**  
- Build **Dash/Streamlit app** for interactive segmentation  
- Integrate with **marketing automation tools**  

---

