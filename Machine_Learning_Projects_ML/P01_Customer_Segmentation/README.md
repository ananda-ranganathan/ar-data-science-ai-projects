# Customer Segmentation using Python (Machine Learning(K-Means Clustering))

## Project Overview:

Our project focuses on customer segmentation for a retail mall using unsupervised machine learning (K-Means clustering). The goal is to group customers based on their age, annual income, and spending behavior so that businesses can better understand customer patterns and design targeted marketing strategies.

## Situation and How used in Real-World:

In real-world business scenarios, malls collect customer info like age, gender, annual income, and spending behavior. However, raw data alone isn’t actionable — marketing teams need targeted segments to design personalized strategies and drive revenue.

## Tasks:
1. Load and explore the customer dataset.
2. Clean and preprocess the data.
3. Perform exploratory data analysis (EDA) to understand customer patterns.
4. Use clustering algorithms (like K-Means) to segment the customers.
5. Evaluate and interpret the resulting customer groups.

## Actions Taken

### 1. **Data Loading & Inspection**
- Imported customer dataset containing attributes like age, income, and spending scores.
- Checked for missing values and data types.
- Examined the initial structure of the dataset.

### 2. **Data Cleaning & Preprocessing**
- Handled missing or inconsistent values.
- Selected relevant features for clustering.
- Standardized numerical features to ensure fair distance calculations.

### 3. **Exploratory Data Analysis**
- Visualized distributions of key features using histograms and box plots.
- Analyzed relationships between variables like age, income, and spending patterns.

### 4. **Clustering with K-Means**
- Applied the **Elbow Method** to find an optimal number of clusters.
- Trained a **K-Means clustering model** on scaled features.
- Labeled customers with their cluster assignments.

### 5. **Cluster Interpretation**
- Plotted the clusters in two dimensions to visualize group separation.
- Examined cluster centroids to summarize characteristics of each segment.

## DataSets Acquisition:

Use the Mall Customers dataset from Kaggle with 200 customers.

### *Features*: 

CustomerID, Gender, Age, Annual Income (k$), Spending Score (1–100).

## Data Preview:

<img width="717" height="220" alt="image" src="https://github.com/user-attachments/assets/90a263a6-1c82-4059-8ac9-db6a28856c43" />

### Exploration & Analysis:

1) Inspect structure, summary statistics, and distributions of variables.

2) Visualize important features using bar plots, histograms, pie charts, and box plots.

## 📊 Visual Highlights

###  Elbow Method to determine optimal clusters
<p align="center">
  <img src="https://github.com/user-attachments/assets/4f99b550-a649-4bdb-8215-efd05afdb4b5" width="600"/>
</p>

###  Final Cluster Visualization
<p align="center">
  <img src="https://github.com/user-attachments/assets/4c062c2c-0cea-42bf-a494-0c93b401df35" width="600" />
</p>

# *Exploratory Data Analysis(EDA):*

Using the Mall Customers dataset, exploratory data analysis (EDA) is performed to understand customer distributions and relationships between variables. Multiple clustering evaluation techniques—Elbow Method, Silhouette Score, and Gap Statistic—are applied to determine the optimal number of clusters.

## **Implement K-Means Clustering:**

1) Choose K (number of clusters) manually and with statistical methods.

2) Assign each customer to a cluster by minimizing distances to centroids using Euclidean distance.
   
## **Interpret and Visualize Clusters:**

1) Analyze cluster profiles (income, spending patterns, age trends).

2) Visualize clusters via scatter plots and colors to identify distinct customer types.

## 📈 Key Results

✨ The model successfully grouped customers into distinct segments based on spending behavior and demographic traits.

✔ Customers with similar **spending patterns** and **income levels** are grouped together.  
✔ The segmentation helps in identifying:
- **High-value customers**
- **Low-spending but potential growth groups**
- **Moderate spenders requiring tailored engagement**

These clusters can inform marketing strategy, personalized campaigns, and product recommendations — leading to higher ROI.

### **The Final Output:**

The final output provides distinct customer segments such as high-value customers, average spenders, and low-engagement customers, enabling data-driven decision-making for promotions, customer retention, and revenue optimization.

K-Means clustering has successfully segmented customers into distinct groups based on their age, income, and spending patterns. These insights provide a valuable foundation for targeted marketing strategies and improved customer engagement. The visualizations, including the 3D scatter plot, clearly illustrate the differences between clusters, empowering businesses to make data-driven decisions and tailor their approaches effectively.

## 🧠 Tools & Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook / VS Code**

## 📂 Project Structure

<img width="555" height="704" alt="image" src="https://github.com/user-attachments/assets/75db23cd-da9a-439d-8bd5-5df3468ea21c" />

## 📌 Conclusion

This customer segmentation project successfully used unsupervised learning techniques to group customers based on similarity in behavior. The results provide valuable business insights for targeted marketing and strategic decision-making.

