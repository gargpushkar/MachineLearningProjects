descriptionProblem:
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Approach:
Text data is a highly unstructured form of data, various types of noise are present in it and the data is not readily analyzable without any pre-processing. 
Since the data contained noise, text data was cleaned with following steps:
1. Removed Twitter Handles (@user)
2. Removed Punctuation, Numbers, and Special Characters
3. Removed Short Words
4. Text Normalization

The cleaned text was converted to features using 2 approaches:
1. Bag of Words
2. TF-IDF

Finally, the model was built on the following methods:
1. Logistic Regression
2. Support Vector Machine(SVM)
3. Random Forest
4. XGBoost

The evaluation metric used for this problem is F1-Score.

Technologies Used: 
Python, Libraries: Pandas, Matplotlib, NumPy, SciPy, Scikit, NLTK ,Seaborn.
