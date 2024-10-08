# Social_Network_Ads
 The goal of this project is to build a machine learning model that classifies whether a user purchased a product based on their social network profile data, including features such as age, gender, and estimated salary.
Preprocessing:
Dropped irrelevant columns: The User ID column was dropped as it does not contribute to the prediction.
Handling missing values: Checked for missing values (none were found).
Encoding categorical variables: The Gender column was label-encoded (Male = 0, Female = 1).
Standardization: Features were scaled using StandardScaler to improve model performance.
Exploratory Data Analysis (EDA):
Pairplot: Visualized relationships between features and target variables.
Scatterplot: Showed the relationship between Age, Estimated Salary, and the Purchased status.
Boxplot: Compared the distribution of EstimatedSalary for purchased and non-purchased groups.
Countplot: Displayed the distribution of the target variable, Purchased (imbalanced data).
Model 1: Logistic Regression
Train-Test Split: Data was split into training (80%) and testing (20%) sets.
Model Training: Logistic Regression was trained on scaled data.
Results:
Training accuracy: 84.86%
Testing accuracy: 81.25%
Model 2: K-Nearest Neighbors (KNN)
Model Training: KNN classifier was trained with 5 neighbors.
Results:
Training accuracy: 92.11%
Testing accuracy: 93.75%
Conclusion:
The KNN model performed better than Logistic Regression, achieving higher accuracy on both the training and testing datasets. This model can be used to predict user purchasing behavior based on their social network profile attributes.
