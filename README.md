# Identifying Customer Behaviour Through K Means Algorithm

## Project Description
This project focuses on analyzing and identifying customer behavior for a clothing company using **customer segmentation** techniques. Through Exploratory Data Analysis (EDA) and **K-Means clustering**, this project aims to uncover distinct customer groups and provide actionable business insights that help in targeted marketing and decision-making.

---

## Objectives
- Perform an in-depth **Exploratory Data Analysis (EDA)** to understand variable distributions and relationships.  
- Apply **K-Means clustering** to segment customers based on behavioral and demographic features.  
- Analyze each cluster’s characteristics and provide **actionable insights** for business strategies.

---

## Dataset Information
- Total observations: **3,900**  
- Total features: **18 columns**  
- Data types: mixture of numerical (integer, float) and categorical (object).  
- Unique identifier: **Customer ID**  
- No missing values detected.  
- Dataset includes various customer attributes related to spending behavior, income, and shopping preferences.

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Inspected dataset structure, column datatypes, and overall composition.  
- Confirmed there are no missing values.  
- Performed **outlier detection** to ensure data consistency.  
- Examined variable distributions and correlations using visualization tools such as `matplotlib` and `seaborn`.

### 2. Data Preprocessing
- Applied **Label Encoding** and **One-Hot Encoding** for categorical variables.  
- Scaled numerical features using **StandardScaler** to normalize value ranges.  
- Removed low-variance features using **VarianceThreshold**.  
- Conducted **PCA (Principal Component Analysis)** to reduce dimensionality and improve clustering performance.

### 3. Modeling – K-Means Clustering
- Implemented **K-Means** to group customers into optimal clusters.  
- Determined the best number of clusters using **Elbow Method** and **Silhouette Score**.  
- Evaluated clustering performance and interpretability.

### 4. Cluster Interpretation
- Analyzed each cluster’s characteristics based on demographic and behavioral features.  
- Identified patterns in customer spending, income, and preferences.  
- Summarized clusters into meaningful business profiles.

---

## Results and Findings
- The optimal number of clusters was determined using the **Elbow Method** and **Silhouette Score**.  
- Each cluster showed distinct behavioral traits, indicating clear segmentation in customer preferences.  
- The analysis provided insights such as which customer segments are more likely to spend higher amounts or respond better to promotions.  
- Clustering results can be used to support **targeted marketing**, **personalized offers**, and **customer retention strategies**.

---

## Conclusion
This project demonstrates how **unsupervised learning** using K-Means clustering can effectively uncover customer segments for a clothing company. By combining EDA, feature preprocessing, and clustering techniques, the analysis helps businesses understand their customers better and make data-driven decisions to enhance marketing strategies.
