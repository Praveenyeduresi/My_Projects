## Project Title : Fake News Detection using Machine Learning & Deep Learning techniques.

**Technologies Used**: 
**Libraries**: Pandas, NumPy, Matplotlib, Seaborn, NLTK, Scikit-learn, tensorflow, Pickle.---
**Languages**: Python.---
**Deployment**: Pickle.

**Overview**:The main aim of this project is to identify the news articles whether it is fake or true news based on text. By leveraging Natural Language Processing (NLP) and both machine learning and deep learning techniques to predict the fake news. Therefore, misinformation can be reduced.

**The project follows several steps:**

**Data Preprocessing:** handled missing data, Text cleaning, Text normalization, Removed stop words, Tokenization, Stemming, Lemmatization and feature engineering to prepare the data.

**Exploratory Data Analysis**: performed univariant and bivariant analysis.

**Observations in univariant analysis** - Data contains 54% of churn customers and 46% of retained customers which implies target variable distribution is balanced. Text length and word count have a right-skewed distribution, with most articles averaging around 1500 characters and around 250 words respectively. The subject distribution shows a high concentration in the "politics" category.

**Observations in Bivariant analysis** - True news articles tend to have slightly longer text lengths and higher word counts, moreover, Articles under "politicsNews" are more likely to be true news. while fake news is more common in certain subject categories like "News." Both text length and word count show weak correlations with the Target variable.

**Text Vectorization**:TF-IDF (Term Frequency-Inverse Document Frequency)

**Machine Learning Models:** Trained and evaluated multiple models like Logistic Regression, Support Vector Machines (SVM) and Naive Bayes.

**Deep Learning Approach:** Integrated a Long Short-Term Memory (LSTM) network, a type of recurrent neural network (RNN), to capture sequential patterns and context in textual data.

**Model Evaluation:** Evaluated models using metrics like accuracy, precision, recall, F1-score and confusion matrix.

**Deployment**: Saved the trained Logistic Regression model using pickle for deployment.

**Manual Testing**: Whether News is Fake or Not a Fake 

**Conclusion**: 
This project focused on identifying true and fake news using natural language processing techniques. The text data was cleaned and prepared for analysis using extreme preprocessing techniques such tokenization, stop word removal, and lemmatization. Exploratory data analysis showed patterns like the frequency of political news and variations in text characteristics between true and fake news articles. During modelling stage, performed evaluation metrics such as accuracy, precision, recall, and F1-score. Based on the results, Support Vector Classifier (SVC) and Logistic Regression achieved the highest accuracies, with 99% and 98% respectively. These findings demonstrate that machine learning and deep learning models can effectively leverage such insights to enhance fake news detection systems.
