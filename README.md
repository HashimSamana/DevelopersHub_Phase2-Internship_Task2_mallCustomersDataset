# Task 2: Customer Segmentation Using K-Means Clustering

## Objective
Segment mall customers based on spending habits to design targeted marketing strategies.

## Dataset
**Mall Customers Dataset** containing:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Approach
1. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of Age, Annual Income, and Spending Score.
   - Visualized spending patterns across customers.

2. **Feature Selection & Scaling**
   - Selected `Annual Income` and `Spending Score` as features.
   - Scaled features using StandardScaler for clustering.

3. **K-Means Clustering**
   - Determined optimal number of clusters using Elbow Method.
   - Clustered customers into 5 segments.

4. **Dimensionality Reduction**
   - Used PCA to reduce features to 2 dimensions for visualization.
   - Visualized clusters in 2D scatter plot.

5. **Segment Analysis**
   - Calculated average income and spending score per cluster.
   - Suggested marketing strategies for each segment:
     - High spenders → Premium promotions
     - Low spenders → Discount campaigns
     - Moderate spenders → Loyalty programs

## Tools & Libraries
- Python, pandas, numpy, matplotlib, seaborn, scikit-learn

## Insights
- Customer segmentation helps tailor marketing campaigns to different spending behaviors.
- Visualization and PCA made clusters easy to interpret.
