# Customer Segmentation with K-Means and K-Nearest Neighbors 

#### Project Status: Complete

## Outcome
* Applied K-Means to the Customer data and identified 4 underlying segments: 
  1. low income ($20-40k) & low spending score (0-40)
  2. low income ($20-40k) & high spending score (40-100)
  3. high income ($40-140k) & low spending score (0-40)
  4. high income ($40-140k) & high spending score (40-100)
 * Used GridSearchCV to optimize the best K-Nearest Neighbors model resulting in 97% accuracy. The lowest precision was 93% and that was for predicting cluster #2 (low income and high spending). This group was split in the K-Means model of 5 clusters and contains customers with median income and spending score. 
 * Compared the KNN model to Logistic Regression (95% accuracy) and Random Forest (98% accuracy).

## Methods & Technology
* **Language**: Python
* **Data Format**: CSV
* **Data Processing**: Pandas, Numpy
* **Machine Learning**: Scikit-learn (KMeans, GridSearchCV, KNeighborsClassifier, Logistic Regression, RandomForestClassifier)
* **Data Visualization**: Matplotlib, Seaborn, Axes3D

## Contact
* Email: [cityofbrittany@gmail.com](cityofbrittany@gmail.com)
* LinkedIn: [linkedin.com/in/brittanycity](https://www.linkedin.com/in/brittanycity/)
