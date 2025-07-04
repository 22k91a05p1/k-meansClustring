Customer Segmentation using K-Means Clustering
📌 Objective
Perform unsupervised learning using K-Means clustering to segment customers based on their Annual Income and Spending Score.

📁 Dataset
Filename: Mall_Customers.csv

Rows: 200

Columns: 5

Attributes:

CustomerID: Unique ID of each customer.

Gender: Gender of the customer.

Age: Age in years.

Annual Income (k$): Annual income in $1000s.

Spending Score (1-100): Score based on spending habits.

🧠 Algorithms & Tools Used
K-Means Clustering (sklearn.cluster.KMeans)

Silhouette Score for evaluation

Elbow Method to find optimal number of clusters (K)

Libraries:

pandas, matplotlib, seaborn, scikit-learn

🧪 Steps Performed
1. Load and Explore the Dataset
Imported CSV using pandas.

Explored the structure with df.info() and df.head().

2. Preprocessing
Selected only numerical columns:
Annual Income (k$) and Spending Score (1-100) for clustering.

3. Elbow Method to Determine Optimal K
Plotted Within-Cluster Sum of Squares (Inertia) for K = 1 to 10.

Identified the "elbow point" to find the best K.

4. K-Means Clustering
Applied KMeans algorithm with optimal K.

Cluster labels assigned to each customer.

5. Visualization
Scatter plot showing clusters with distinct colors.

X-axis: Annual Income, Y-axis: Spending Score

6. Evaluation
Calculated Silhouette Score to measure clustering quality.

📊 Outputs
Clustered Data: Each customer is assigned a cluster.

Scatter Plot: Visual depiction of customer segments.

Silhouette Score: Indicates how well the clusters are separated.

📌 Conclusion
K-Means effectively segments mall customers based on their income and spending behavior, which can help in:

Personalized marketing

Budget allocation

Customer behavior analysis
