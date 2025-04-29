# Customer-Segmentation-Using-Clustering
This project performs customer segmentation using K-Means and Hierarchical Clustering techniques on the Mall Customer Segmentation dataset. It includes Exploratory Data Analysis (EDA), cluster visualization, and detailed interpretation of customer groups based on age, income, and spending behavior.

Technologies Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (KMeans, StandardScaler, PCA), Scipy (Hierarchical Clustering).

Dataset: Mall Customer Segmentation Dataset (File included in this repository - Mall_Customers.csv)
Dataset Features: CustomerID, Genre, Age, Annual Income (k$), Spending Score (1–100).

Project Workflow:
    Exploratory Data Analysis (EDA): Dataset overview, Data cleaning, Statistical summaries, Feature understanding.
    Clustering:
        K-Means Clustering: Used Elbow Method to determine optimal number of clusters, Built and analyzed clusters.
        Hierarchical Clustering: Built dendrogram, Performed Agglomerative Clustering.
    Visualization:
        Scatter plots showing customer clusters
        Cluster averages interpretation
    Business Insights:
        Identified luxury spenders, cautious rich customers, young impulsive buyers, etc.

Key Results:
    5 customer segments were identified based on age, income, and spending score.
    Valuable patterns for marketing strategies:
        Target high spenders with luxury products.
        Offer promotions to cautious or low spenders to increase sales.
