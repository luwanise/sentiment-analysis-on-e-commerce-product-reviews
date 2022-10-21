This project involves performing sentiment analysis on Women's Clothing E-Commerce dataset obtained from Kaggle. The dataset focuses on reviews written by customers and has 23486 rows and 10 features namely:
- Clothing ID
- Age
- Title
- Review Text
- Rating
- Recommended IND
- Positive Feedback Count
- Division Name
- Department Name
- Class Name

The Review Text feature was classified as either positive or negative using the Rating feature. Ratings of 4 and 5 were labelled as positive while ratings of 1 and 2 were labelled as negative. Two methods were used to convert the reviews text into vector format: TFIDF Vectorizer and Count Vectorizer. The following machine learning algorithms were used in this experiment:

- Random Forests
- Decision Tree
- Gradient Boosting
- Logistic Regression
- Support Vector Machine