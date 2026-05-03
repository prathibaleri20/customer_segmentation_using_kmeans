7. System Architecture 
Flow: 
1. Data Collection  
2. Data Preprocessing  
3. Feature Selection  
4. Clustering Algorithm  
5. Model Training  
6. Cluster Visualization  
7. Analysis & Interpretation  
8. Methodology (Step-by-Step) 
Step 1: Data Collection 
• Collect customer data from:  
o Retail stores  
o E-commerce platforms  
o CSV/Excel datasets  
Step 2: Data Preprocessing 
• Handle missing values  
• Encode categorical data (e.g., Gender → 0/1)  
• Normalize/scale data  
Step 3: Feature Selection 
Select relevant features such as: 
• Annual Income  
• Spending Score  
• Age  
Step 4: Finding Optimal Clusters (Elbow Method) 
Use the Elbow Method to find the best value of K (number of clusters): 
WCSS=∑i=1K∑x∈Ci(x−μi)2WCSS = \sum_{i=1}^{K} \sum_{x \in C_i} (x - 
\mu_i)^2WCSS=∑i=1K∑x∈Ci(x−μi)2 
• Plot WCSS vs number of clusters  
• Choose point where curve bends (elbow point)  
Step 5: Apply K-Means Clustering 
Algorithm steps: 
1. Select K (number of clusters)  
2. Initialize centroids  
3. Assign data points to nearest centroid  
4. Update centroids  
5. Repeat until convergence  
Step 6: Model Training 
• Train K-Means model using dataset  
• Assign cluster labels to each customer  
Step 7: Visualization 
• Plot clusters using graphs:  
o Income vs Spending Score  
• Different colors represent different clusters  
Step 8: Interpretation 
Analyze clusters: 
• Cluster 1 → High income, high spending  
• Cluster 2 → Low income, low spending  
• Cluster 3 → Moderate customers  
9. System Modules 
1. Data Input Module  
2. Data Processing Module  
3. Clustering Module  
4. Visualization Module  
5. Analysis Module 
