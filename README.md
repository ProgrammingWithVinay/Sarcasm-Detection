# Sarcasm Detection

##### This is a project that uses a dataset from Kaggle to classify the sentences are sarcastic or non sarcastic. The project is implemented using Python.

## Data Preprocessing
We started by preprocessing the dataset. We used label encoding, word tokenization, stemming, and removed stop words to extract relevant features from the source code. This allowed us to create a dataset of cleaned code snippets, which we could use for further analysis.

## Vectorization
We then used the Universal Sentence Encoder to convert the cleaned code snippets into vectors. The Universal Sentence Encoder is a method for converting text data into numerical vectors. We used this to represent each code snippet as a vector, which allowed us to perform similarity calculations.

## Model Selection
We used grid search cross-validation to compare the performance of different machine learning models. We evaluated models like SVM, Random Forest, and KNN to identify the best model for the task.

## Results
After comparing the performance of different models, we found that the SVM model achieved the highest accuracy of 87.65%. This indicates that it is a suitable model for the task of source code plagiarism detection.

## Conclusion
Overall, this project demonstrates the power of using data preprocessing, vectorization, and machine learning models for source code plagiarism detection. By using these techniques, we were able to create a system that can accurately detect plagiarism in source code.
