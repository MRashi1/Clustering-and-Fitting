# Clustering-and-Fitting

The Iris dataset consists of 150 instances of iris flowers, each belonging to one of three species: Iris setosa, Iris versicolor, and Iris virginica. The dataset contains four numerical features: sepal length, sepal width, petal length, and petal width, measured in centimeters. The goal of analyzing this dataset is to explore the relationships among these features and to investigate the ability to distinguish the three species based on these measurements.
Each of the three species—Iris setosa, Iris versicolor, and Iris virginica—has an equal distribution of 33.3% in the pie chart for the 'Species' column, with 50 examples for each. The 'SepalLengthCm' histogram shows a range of values from about 4.3 to 7.9, with 5.0 to 5.5 showing the highest frequency.

The three species are clearly distinguished by the scatter plot. Sepal lengths of 4.9–7.0 and petal widths of 1.0–1.8 are normal for Iris versicolor. Sepal lengths of Iris-setosa vary from approximately 4.3 to 5.8, while petal widths range from 0.1 to 0.6. The sepal lengths and petal widths of Iris virginica range from 4.9 to 7.9. Strong positive correlations can be seen in the heatmap, with the correlation between petal length and width having the greatest value (0.96).

Strong positive connections between sepal length and other parameters are displayed in the correlation matrix's heatmap, with the largest correlation (0.96) found between petal length and width.

The silhouette plot displays the scores for the various values of k, or the number of clusters. At k=3, the silhouette with the greatest score—roughly 0.55—is obtained. This shows that three is the ideal number of clusters for the dataset in question, which corresponds to the three different species seen in the Iris dataset.

After running the k-means clustering method with k=3, the following cluster assignments are obtained:
Cluster 0 (Iris-setosa): 50 instances
Cluster 1 (Iris-versicolor): 47 instances
Cluster 2 (Iris-virginica): 53 instances
The dataset is divided into a test set of 30 instances and a training set of 120 instances for the purpose of linear regression. The 'PetalWidthCm' target variable is predicted by the fitted linear regression model, which has an intercept of -0.12 and a coefficient of 0.63 for the 'PetalLengthCm' feature. On the test set, the model achieves an R-squared value of 0.94 and a mean squared error (MSE) of 0.03, indicating an excellent match.

In summary, the examination of the Iris dataset through a range of visualization methods, clustering, and linear regression modeling has yielded significant insights into the associations among the attributes and the capacity to differentiate between the three varieties of iris blooms. The dataset's usefulness for machine learning and data analysis applications is demonstrated by the balanced representation of the species, the distinct separation based on measurements of sepal length and petal width, the efficient clustering and predictive modeling outcomes, and more.
