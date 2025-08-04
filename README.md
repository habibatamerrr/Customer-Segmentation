 📊 Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment mall customers based on their **Annual Income** and **Spending Score**. The goal is to discover meaningful customer groups that businesses can use for targeted marketing and better customer understanding.

📁 Dataset

- **Source**: [Mall Customers Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- **Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

🎯 Objectives

- Clean and prepare the data
- Encode categorical features
- Scale numerical features using `StandardScaler`
- Use the **Elbow Method** to determine the optimal number of clusters (k)
- Apply **K-Means Clustering**
- Visualize the resulting customer segments
- Analyze average spending and income per cluster

🔧 Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-learn

📊 Steps & Methodology

1. **Data Loading & Exploration**
   - Read and inspect the dataset
   - Check for missing values and duplicates

2. **Data Preprocessing**
   - Encode the `Gender` column using LabelEncoder
   - Select `Annual Income` and `Spending Score` as clustering features
   - Scale the features with `StandardScaler`

3. **Modeling**
   - Apply K-Means Clustering with different k values (1 to 10)
   - Use the **Elbow Method** to choose the best number of clusters

4. **Results Visualization**
   - Plot clusters in a 2D scatter plot
   - Color-coded groups based on cluster label

5. **Analysis**
   - Compare the average income and spending score of each cluster

📌 Output Example

![Clusters Plot](path/to/your/image.png)

> Replace this line with your actual cluster plot if you'd like.

🚀 Bonus Ideas

- Try different clustering algorithms like **DBSCAN**
- Cluster based on more features like `Age`, `Gender`, or `CustomerID`
- Create a dashboard to explore clusters interactively

🙋‍♀️ Author

- **Habiba Tamer**  
- [LinkedIn](https://www.linkedin.com/in/habiba-tamer-15785b269/)  
- [GitHub](https://github.com/habibatamerrr)



