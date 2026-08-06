# 🛍️ Customer Segmentation Analysis using K-Means Clustering

## 📖 Overview

Customer segmentation is a powerful business strategy that helps organizations understand customer behavior by dividing customers into distinct groups based on similar characteristics. In this project, the **K-Means Clustering** algorithm is applied to the **Mall Customers Dataset** to segment customers based on their **Annual Income** and **Spending Score**.

The generated customer segments can help businesses develop targeted marketing strategies, improve customer retention, and enhance overall business decision-making.

---

## 🎯 Objectives

- Load and explore the customer dataset.
- Clean and preprocess the data.
- Select relevant features for clustering.
- Standardize numerical features.
- Determine the optimal number of clusters using the Elbow Method.
- Apply the K-Means clustering algorithm.
- Visualize customer segments.
- Profile each customer cluster.
- Generate business insights and marketing recommendations.

---

## 📂 Dataset

**Dataset:** Mall Customers Dataset

**Source:** Kaggle

### Dataset Features

| Feature | Description |
|---------|-------------|
| CustomerID | Unique identifier for each customer |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income of the customer |
| Spending Score (1-100) | Spending score assigned by the mall |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading
- Imported the dataset.
- Examined dataset structure and data types.

### 2. Data Cleaning
- Checked for missing values.
- Removed duplicate records.
- Verified data consistency.

### 3. Feature Selection
Selected the following features for customer segmentation:
- Annual Income (k$)
- Spending Score (1-100)

### 4. Data Standardization
Applied **StandardScaler** to normalize the selected features before clustering.

### 5. Elbow Method
Used the Elbow Method to determine the optimal number of clusters (**K = 5**).

### 6. K-Means Clustering
Applied the K-Means algorithm to group customers into five distinct clusters.

### 7. Cluster Visualization
Visualized customer segments using scatter plots and cluster centroids.

### 8. Cluster Profiling
Analyzed each cluster based on:
- Average Age
- Annual Income
- Spending Score
- Number of Customers

### 9. Customer Distribution
Created a bar chart showing the number of customers in each cluster.

### 10. Business Insights
Generated meaningful insights from the identified customer segments.

### 11. Marketing Recommendations
Suggested targeted marketing strategies for each customer segment.

---

## 📈 Results

The K-Means algorithm successfully segmented customers into **five distinct groups**:

- 💎 Premium Customers
- 😊 Average Customers
- 🛍️ Young High Spenders
- 💰 Careful Customers
- 💵 Budget Customers

These customer segments provide valuable insights that can help businesses improve customer engagement, optimize marketing campaigns, and increase revenue.

---

## 📊 Visualizations

The project includes the following visualizations:

- Elbow Method Plot
- Customer Segmentation Scatter Plot
- Cluster Centroid Visualization
- Customer Distribution Bar Chart

---

## 💡 Business Insights

- Premium customers have both high income and high spending scores, making them the most valuable customer segment.
- Average customers form the largest customer group and contribute consistently to business revenue.
- Careful customers possess high purchasing power but exhibit lower spending behavior, making them ideal candidates for personalized promotions.
- Young high spenders are likely to respond positively to trendy products and loyalty programs.
- Budget customers are price-sensitive and can be engaged through discounts and value-based offers.

---

## 🚀 Future Improvements

- Include additional customer attributes for more comprehensive segmentation.
- Compare K-Means with other clustering algorithms such as DBSCAN and Hierarchical Clustering.
- Build an interactive dashboard using Streamlit or Power BI.
- Deploy the project as a web application.

---

## 📁 Project Structure

```text
Customer-Segmentation-Analysis/
│
├── customer_segmentation.ipynb
├── Mall_Customers.csv
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/OIBSIP.git
```

2. Navigate to the project directory.

```bash
cd OIBSIP/DataAnalytics-L1-Customer-Segmentation-Analysis
```

3. Launch Jupyter Notebook.

```bash
jupyter notebook
```

4. Open **Customer_Segmentation.ipynb**.

5. Run all cells sequentially to reproduce the results.

---

## 🎓 Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Data Standardization
- K-Means Clustering
- Elbow Method
- Cluster Profiling
- Data Visualization
- Business Analytics
- Marketing Strategy Development

---

## 👩‍💻 Author

**Pallavi Sagar**

Aspiring **Data Analyst | AI Enthusiast | Machine Learning Learner**

---

## ⭐ Acknowledgements

- Kaggle for providing the **Mall Customers Dataset**.
- Scikit-learn for the K-Means clustering implementation.

---

⭐ If you found this project helpful, consider giving it a star on GitHub.
