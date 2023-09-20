# Support Vector Machine
Support Vector Machine (SVM) is a powerful machine learning algorithm used for linear or nonlinear classification, regression, and even outlier detection tasks. SVMs can be used for a variety of tasks, such as text classification, image classification, spam detection, handwriting identification, gene expression analysis, face detection, and anomaly detection. SVMs are adaptable and efficient in a variety of applications because they can manage high-dimensional data and nonlinear relationships.

The main objective of the SVM algorithm is to find the optimal hyperplane in an N-dimensional space that can separate the data points in different classes in the feature space.
SVMs work by finding the maximum separation or margin between two classes. The best hyperplane is chosen as the one that represents the largest separation or margin between the two classes. SVMs are robust to outliers and can ignore them while finding the best hyperplane that maximizes the margin.

## Implementation
- Importing the required Libraries
- Reading the dataset
- Performing EDA on the dataset
- Applying Visualizations on the data
- Data Preprocessing
- Splitting the data into Train and Test data
- Standardization of the data
- Building SVM Classifier Model and finding the Accuracy
  - using Kernel - **'rbf'**
  - using Kernel - **'linear'**
  - using Kernel - **'poly'**
  - using Kernel - **'sigmoid'**
- Conclusion

## Packages Used
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- warnings
- from sklearn import svm
- from sklearn.svm import SVC
- from sklearn.preprocessing import StandardScaler, LabelEncoder
- from sklearn.model_selection import GridSearchCV, train_test_split, cross_val_score
- from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
