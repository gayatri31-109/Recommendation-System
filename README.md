🛍️ Customer Segmentation & Product Recommendation System
📌 Project Overview

This project performs Customer Segmentation and Personalized Product Recommendation using the Online Retail dataset. The objective is to analyze customer purchasing behavior, identify distinct customer groups, and recommend products based on cluster-level buying patterns.

The project combines:

Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Outlier Detection
Dimensionality Reduction (PCA)
Customer Segmentation using K-Means Clustering
Product Recommendation System
🎯 Objectives
Understand customer purchasing behavior.
Detect and remove anomalous customers.
Group customers into meaningful segments.
Visualize customer clusters.
Generate personalized product recommendations.
Support targeted marketing and customer retention strategies.
📂 Dataset

Dataset: Online Retail Dataset

The dataset contains transactional records including:

Feature	Description
InvoiceNo	Invoice Number
StockCode	Product Code
Description	Product Description
Quantity	Quantity Purchased
InvoiceDate	Transaction Date
UnitPrice	Product Price
CustomerID	Customer Identifier
Country	Customer Country
⚙️ Workflow
1. Data Preprocessing
Removed missing values
Removed duplicate records
Handled cancelled transactions
Converted date columns into proper datetime format
2. Exploratory Data Analysis (EDA)

Analyzed:

Missing values
Transaction patterns
Revenue distribution
Country-wise sales
Customer purchasing trends
3. Feature Engineering

Created customer-level features such as:

Total Transactions
Total Spend
Average Transaction Value
Unique Products Purchased
Customer Country
Cancellation Rate
Monthly Spending Trends
4. Outlier Detection

Used:

Isolation Forest

Purpose:

Detect abnormal customer behavior
Improve clustering quality
5. Feature Scaling

Applied:

StandardScaler

to normalize numerical features.

6. Dimensionality Reduction

Used:

Principal Component Analysis (PCA)

Benefits:

Reduced feature dimensions
Improved clustering performance
Easier visualization
7. Customer Segmentation

Algorithm:

K-Means Clustering

Optimal number of clusters determined using:

Elbow Method
Silhouette Analysis

Final clusters:

Cluster 0
Cluster 1
Cluster 2
8. Product Recommendation System

Generated recommendations by:

Identifying popular products within each customer cluster.
Recommending products frequently purchased by similar customers.
🧰 Technologies Used
Programming Language
Python
Libraries
NumPy
Pandas
Matplotlib
Seaborn
Plotly
Scikit-Learn
Yellowbrick
Tabulate
📊 Machine Learning Models
Isolation Forest

Used for:

Outlier Detection
PCA

Used for:

Dimensionality Reduction
K-Means Clustering

Used for:

Customer Segmentation
📈 Evaluation Metrics

Cluster quality evaluated using:

Silhouette Score
Calinski-Harabasz Index
Davies-Bouldin Index
📊 Results

The model successfully:

✅ Identified meaningful customer segments

✅ Removed anomalous customer behavior

✅ Reduced data dimensionality while preserving information

✅ Generated personalized product recommendations

✅ Provided insights for marketing and customer engagement strategies

🚀 How to Run
Clone Repository
git clone https://github.com/your-username/customer-segmentation-recommendation.git
cd customer-segmentation-recommendation
Install Dependencies
pip install numpy pandas matplotlib seaborn plotly scikit-learn yellowbrick tabulate
Run Jupyter Notebook
jupyter notebook

Open:

Prj2.ipynb

and run all cells.

📷 Sample Outputs
Customer Distribution Analysis
Missing Value Analysis
PCA Explained Variance Plot
K-Means Cluster Visualization
Cluster Profiles
Product Recommendations
🔮 Future Improvements
Implement RFM Analysis
Deep Learning-based Recommendations
Real-Time Recommendation Engine
Interactive Dashboard using Streamlit
Deployment on Cloud Platforms
👨‍💻 Author

Gayatri Choudhary

Customer Analytics | Machine Learning | Data Science
