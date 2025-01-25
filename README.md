# eCommerce-Transaction-Dataset-Business-Analysis
This project analyzes an eCommerce transaction dataset to derive business insights. It includes customer segmentation using K-Means clustering, exploratory data analysis, and clustering evaluation metrics like Silhouette Score. The project provides actionable strategies for targeted marketing and business growth through data-driven decision-making.


## Objectives  
1. Perform customer segmentation using K-Means clustering.  
2. Analyze transaction patterns for business insights.  
3. Evaluate clustering performance with metrics.  
4. Provide recommendations for targeted marketing and customer engagement.


## Dataset   
**Files Used**:  
  1. **Customers.csv**  
     - **CustomerID**: Unique identifier for each customer.  
     - **CustomerName**: Name of the customer.  
     - **Region**: Continent where the customer resides.  
     - **SignupDate**: Date when the customer signed up.  

  2. **Products.csv**  
     - **ProductID**: Unique identifier for each product.  
     - **ProductName**: Name of the product.  
     - **Category**: Product category.  
     - **Price**: Product price in USD.  

  3. **Transactions.csv**  
     - **TransactionID**: Unique identifier for each transaction.  
     - **CustomerID**: ID of the customer who made the transaction.  
     - **ProductID**: ID of the product sold.  
     - **TransactionDate**: Date of the transaction.  
     - **Quantity**: Quantity of the product purchased.  
     - **TotalValue**: Total value of the transaction.  
     - **Price**: Price of the product sold.

       
## Tools & Libraries  
- **Languages**: Python  
- **Libraries**:  
  - Pandas, NumPy for data manipulation.  
  - Matplotlib, Seaborn for data visualization.  
  - Scikit-learn for clustering.  


## Procedure  

### 1. **Data Preparation**  
   - Load datasets (`Customers.csv` and `Transactions.csv`).  
   - Handle missing values using appropriate imputation techniques.  
   - Encode categorical variables (e.g., one-hot encoding for regions).  
   - Scale features using Min-Max scaling for clustering algorithms.  

### 2. **Exploratory Data Analysis (EDA)**  
   - Analyze transaction trends (distribution, patterns).  
   - Visualize customer demographics and transaction frequency.  

### 3. **Customer Segmentation**  
   - Apply K-Means clustering to group customers.  
   - Use the Elbow Method to determine the optimal number of clusters.  

### 4. **Cluster Evaluation**  
   - Calculate evaluation metrics:  
     - Silhouette Score  
     - Davies-Bouldin Index  
     - Final Within-Cluster Sum of Squares (WCSS)  
   - Visualize clusters using PCA for dimensionality reduction.  

### 5. **Insights & Recommendations**  
   - Analyze cluster profiles (e.g., high-value customers, low-frequency customers).  
   - Provide actionable recommendations for marketing strategies.  

### 6. **Visualization**  
   - Create detailed plots:  
     - Elbow Plot for optimal clusters.  
     - PCA Scatter Plot for cluster visualization.  
     - Histogram of transaction distributions.  


## Results  
1. **Optimal Clusters**: 4 clusters identified via the Elbow Method.  
2. **Key Metrics**:  
   - Silhouette Score: 0.431  
   - Davies-Bouldin Index: 0.976  
   - Final WCSS: 376.586  
3. **Cluster Profiles**:  
   - High-value frequent shoppers  
   - Moderate regular spenders  
   - Low-value infrequent shoppers  
   - High-value infrequent shoppers  


## Recommendations  
- **Targeted Marketing**: Customize campaigns based on cluster characteristics.  
- **Customer Retention**: Reward high-value frequent shoppers.  
- **Engagement**: Incentivize low-value customers to increase spending.


## Conclusion  
This analysis demonstrates how clustering and transaction insights can drive data-driven business strategies. The project provides a foundation for understanding customer behavior and improving marketing outcomes.
