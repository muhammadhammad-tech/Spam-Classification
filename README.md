# Spam-Classification
Spam Classification using Machine Learning
1. Dataset Loading & Preparation
Loaded the dataset from a CSV file (spam.csv) using Pandas.
Cleaned the dataset by removing unnecessary columns and renaming columns for clarity.
2. Data Cleaning
Dropped irrelevant columns ('Unnamed: 2', 'Unnamed: 3', 'Unnamed: 4').
Encoded the target variable ('spam' and 'ham') using Label Encoding.
Checked and removed any missing values.
Eliminated duplicate entries in the dataset.
3. Exploratory Data Analysis (EDA)
Visualized the distribution of spam and non-spam messages.
Explored data insights using pair plots (though the relevance for text data may be limited).
Detected and visualized outliers in the dataset.
4. Data Preprocessing
Converted text data into a suitable format for modeling.
Applied text preprocessing techniques, including lowercase conversion, tokenization, and removal of special characters, stopwords, and stemming.
5. Word Clouds and Bar Plots
Generated word clouds to visualize most common words in spam messages.
Plotted bar graphs to display the most frequently used words in spam and non-spam messages.
6. TF-IDF Vectorization
Utilized TF-IDF vectorization to convert text data into numerical features.
7. Data Splitting
Split the dataset into training and testing sets for machine learning model training and evaluation.
8. Conclusion
Prepared the dataset for building a machine learning model to classify spam and non-spam messages.
Next Steps
Choose a machine learning model for classification.
Train the model on the training data.
Evaluate the model's performance on the testing data.
Document the model, its performance, and any further optimizations in the README.
