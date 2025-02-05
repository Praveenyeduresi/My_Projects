Project Title : Mobile Price Classification.

Technologies Used: Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, tensorflow, statsmodels, --- Languages: Python.

Project Objective: The aim of this project is to analyze various mobile phone features and determine their impact on price classification. By leveraging machine learning techniques, we aim to classify mobile phones into different price ranges based on key attributes like RAM, battery power, screen resolution, camera quality, and connectivity features. This will help in understanding which factors contribute the most to pricing and assist manufacturers in strategic pricing decisions.

Table of contents

Dataset Loading Data Exploration Data Preprocessing Exploratory Data Analysis (EDA) Modelling Evaluation Metrics Conclusion The project follows a structured pipeline as outlined below:

Data Loading: Load the dataset and inspect its structure.

Data Exploration: Understand the dataset by checking distributions, missing values, datatypes and key statistics.

Data Preprocessing: - There are no challenges in the data.

Exploratory Data Analysis (EDA): performed univariant and bivariant analysis.

Observations in univariant analysis

Most mobiles having dual sim, 4G, 3G, touch secreen, wifi and without bluetooth. But, comparing with 4G network 3G network devices are high. However, Most mobiles have high battery capacity and Majority have lower clock speeds; high-performance processors are fewer. Furthermore, RAM is Skewed distribution with more budget-friendly models having lower RAM. Finally, Pixel Resolution having Wide variation in screen quality, with some having high resolutions.

Observations in Bivariant analysis

Bluetooth and dual SIM support show no significant impact on price range, as they are common across all categories. Higher front and primary camera megapixels are more frequent in expensive phones. 4G support is a key differentiator, with premium models mostly having it. The number of processor cores slightly correlates with higher price ranges. Larger screen height and width are generally found in high-end devices. Talk time does not show a strong relationship with price. 3G support is common across all segments, making it less influential. Touchscreen availability is nearly universal, so it has no major effect on pricing.

Modeling:
Applied various machine learning models: Logistic Regression, DecisionTree, RandomForest, XGBoost, Support Vector Machine (SVM), K-Nearest Neighbors (KNN) & Neural Networks.

Evaluation
The models were evaluated based on classification reports such as precision, Recal, accuracy and F1-score.

Conclusion:
The SVM and KNN models provided the most accurate predictions for mobile price classification, with an accuracy of 0.96 and 0.94 respectively.
