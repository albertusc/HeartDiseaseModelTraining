**Classification Analysis of Cardiovascular Diagnosis with Lifestyle and Demographic Factors: Comparison of Logistic Regression, Lasso Regression, and Ridge Regression**

This Python script conducts an in-depth analysis of heart disease classification using machine learning techniques. It begins by preparing the dataset, handling categorical variables, and addressing missing values. The script explores the data through visualizations, depicting the distribution of heart disease cases and age groups. Following data exploration, it preprocesses the data further, splitting it into features and target variables, encoding categorical features, and partitioning the dataset into training and testing sets.

The core of the analysis lies in model evaluation, where three different algorithms are employed: Logistic Regression, Lasso Regression, and Ridge Regression. These models are evaluated based on various metrics such as accuracy, classification reports, confusion matrics, mean squared error (MSE), R-squared, mean absolute error (MAE), and area under the curve (AUC). Each model's performance is assessed rigorously to understand its predictive capabilities.

Finally, the script compares the models' performance using ROC AUC scores and learning curves. This comparison helps in identifying the most effective model for heart disease prediction. Overall, the script serves as a comprehensive guide to analyzing heart disease prediction using machine learning, offering insights into model performance and aiding in decision-making regarding model selection for real-world applications.

Demographic Factors:
- Sex: Indicator of a person's gender (1 for "male" and 0 for "female").
- AgeCategory: Grouping people into age ranges.
- Race: One's racial background.

Lifestyle Factors:
- Smoking: Indicator of whether a person smokes or not (1 for "Yes" and 0 for "No").
- Alcohol Drinking: Indicator of whether a person has alcohol consumption habits (1 for "Yes" and 0 for "No").
- PhysicalActivity: Indicator of whether or not the person frequently engages in sports activities (1 for "Yes" and 0 for "No").
- SleepTime: Measurement of one's sleep time.

Medical Test Variables:
- Heart Disease: Final result indicating the presence of heart disease (1) or absence (0).
- Stroke: History of stroke (1 for "Yes" and 0 for "No").
- cp: Four types of chest pain.
- trestbps: Blood pressure at rest.
- chol: Cholesterol level in mg/dl.
- fbs: Blood sugar level in mg/dl.
- restecg: Result of the electrocardiograph at rest (values 0, 1, 2).
- thalach: Maximum heart rate achieved.
- exang: Chest pain when exercising or experiencing emotional stress.
- oldpeak: Exercise-induced ST-segment depression, a reliable ECG finding for diagnosing obstructive coronary atherosclerosis.
- slope: Peak training ST segment slope.
- ca: Number of major blood vessels (0-3) stained with fluoroscopy.

Dependent Variable:
- Heart Disease: Presence (1) or absence (0) of cardiovascular disease in the patient.

Dataset Reference:
[heart.csv] - [https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset]
[heart_2020_cleaned.csv] - [https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease?resource=download]
