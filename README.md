
# Credit Card Usage Segmentation  

## 📌 Project Overview  
This project applies **unsupervised machine learning** to segment credit card customers based on their **spending** and **payment behaviors**. The aim is to help financial institutions gain deeper insights into customer profiles, improve **marketing strategies**, and enhance **credit risk assessment**.  

---

## 🎯 Key Goals  
- Identify distinct customer segments using clustering techniques.  
- Understand patterns in spending and repayment.  
- Provide insights that can support **personalized services**, **fraud detection**, and **risk management**.  

---

## 🛠️ Approach  

### 1. Exploratory Data Analysis (EDA)  
- Visualized spending and payment distributions.  
- Analyzed correlations between financial features.  

### 2. Data Preprocessing  
- Handled missing values.  
- Scaled numerical variables for uniformity.  
- Applied feature engineering where relevant.  

### 3. Dimensionality Reduction  
- Used **PCA** and **t-SNE** to project high-dimensional data into 2D for visualization.  

### 4. Clustering Models  
- Implemented **K-Means** and **Agglomerative Clustering**.  
- Evaluated performance with **silhouette score** and **inertia**.  

### 5. Insights & Visualization  
- Plotted clusters to reveal distinct customer groups.  
- Interpreted spending/repayment patterns within each segment.  

---

## 📊 Results & Insights  
- The models successfully separated customers into **meaningful clusters**.  
- Each cluster showed distinct financial behavior, such as:  
  - **High spenders with regular payments**  
  - **Moderate spenders with delayed payments**  
  - **Low spenders with minimal activity**  
- These insights can be directly applied to **targeted marketing** and **risk profiling**.  

---

## 🧑‍💻 Tech Stack  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Techniques:** PCA, t-SNE, K-Means, Agglomerative Clustering  
