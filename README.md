 Objective
The objective of this task is to understand and implement the K-Nearest Neighbors (KNN) algorithm for classification problems. The project focuses on feature normalization, model training, experimenting with different values of K, evaluation using performance metrics, and visualization of decision boundaries.
 Tools and Technologies Used
* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
Iris Dataset (CSV Format)

The Iris dataset contains measurements of iris flowers belonging to three different species. It is widely used for classification problems in machine learning.
* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Species (Setosa, Versicolor, Virginica)
* Dataset uploaded into Google Colab environment.
* Loaded using Pandas DataFrame.
* Dataset explored using:

  * head()
  * info()
  * describe()
* Independent Variables (X): All numerical flower measurements.
* Dependent Variable (y): Species column.

Since KNN depends on distance calculations, feature scaling was performed using StandardScaler to normalize the dataset.
Dataset divided into:

* Training Data (80%)
* Testing Data (20%)

using train_test_split from Scikit-learn.

KNeighborsClassifier was used to train the classification model.

Initial parameter:

* Number of neighbors (K) = 3
Different values of K were tested to analyze model performance.
Observations:
* Small K values may lead to overfitting.
* Larger K values may cause underfitting.
Accuracy vs K graph was plotted using Matplotlib.
 7. Model Evaluation
Model performance evaluated using accuracy score on test dataset.
Confusion Matrix
Confusion matrix used to analyze classification performance and prediction errors.
 8. Decision Boundary Visualization
Decision boundaries were visualized using two selected features to understand how the KNN algorithm separates different classes.

Label encoding was applied to convert categorical species labels into numeric form for visualization.

* Accuracy Score
* Confusion Matrix


* Feature normalization improved classification performance.
* K value selection significantly affected accuracy.
* KNN successfully classified iris flower species with high accuracy.



