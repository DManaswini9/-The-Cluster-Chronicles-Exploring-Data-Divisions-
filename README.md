"The Cluster Chronicles: Exploring Data Divisions"

This machine learning project segments Instagram users based on how often they use the platform and how much they spend. By applying multiple clustering algorithms (K-Means, K-Medoids, and Hierarchical Clustering), it identifies natural patterns in the data to support marketing and engagement strategies.



## 📌 Overview
This project explores the behavioral segmentation of Instagram users by clustering them based on how often they visit the platform and their spending habits. It uses unsupervised learning techniques to reveal natural groupings in the data without prior labels.

## 📁 Dataset
The dataset used is from Kaggle: [Instagram Visit Clustering Dataset](https://www.kaggle.com/datasets/chaandsheikh/instagram-visit-clustering)  
Features:
- **Instagram Visit Score**
- **Spending Rank (0 to 100)**

## 🎯 Objective
To identify distinct user groups such as:
- Highly active and high spenders
- Casual browsers
- Frequent users with low spending

This helps in developing personalized marketing strategies, optimizing content delivery, and better audience targeting.

## 🧠 Techniques Used
- **Data Preprocessing** (Scaling, Cleaning)
- **K-Means Clustering**
- **K-Medoids Clustering**
- **Agglomerative Clustering** (Single & Complete Linkage)
- **Visualization** (Scatter Plots, Dendrograms)
- **Elbow Method** for optimal `K`

## 📊 Key Observations
- Clusters reflect distinct combinations of Instagram usage and spending patterns.
- Hierarchical clustering reveals deeper patterns through dendrograms.
- K-Medoids showed better resistance to outliers compared to K-Means.

## 📎 Tools Used
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn, Scipy)
- Jupyter Notebook

## 📈 Output
- Clear cluster visualizations
- Behavioral insights from clustering analysis
- Interactive plots using Matplotlib

## 🔚 Conclusion
Clustering allows the extraction of meaningful behavioral groups from raw Instagram data. This helps stakeholders understand user tendencies and tailor services accordingly.
