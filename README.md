# classifying-the-Ecommerce-Data.-with-Tf-Idf-text-representation.

Here's a summary of what code does step by step:

## 1.Import the necessary libraries and read the CSV file into a pandas DataFrame.
2.Check the shape and display the first 5 rows of the DataFrame.
3.Check the distribution of labels in the 'label' column.
4.Map the labels to numerical values in a new 'label_num' column.
5.Perform train-test split on the preprocessed text and label data.
6.Create a pipeline for a Multinomial Naive Bayes classifier with TF-IDF vectorization.
7.Fit the pipeline on the training data and make predictions on the test data.
Print a classification report showing precision, recall, and F1-score for each class.
8.Use spaCy to preprocess the text data by removing stopwords and lemmatizing words.
9.Perform another train-test split on the preprocessed text and labels.
10.Create a pipeline for a Random Forest classifier with TF-IDF vectorization and n-gram range specification.
11.Fit the pipeline on the training data and make predictions on the test data.
Print a classification report for the Random Forest classifier.
12.Calculate and display the confusion matrix.
13.Visualize the confusion matrix using a heatmap.





