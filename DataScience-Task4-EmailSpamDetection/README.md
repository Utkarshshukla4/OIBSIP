# Email Spam Detection Using Machine Learning

## Project Overview
This project uses Natural Language Processing (NLP) and machine learning to classify text messages as Spam or Ham (legitimate messages).

## Dataset
- Dataset: SMS Spam Collection
- Source: [SMS Spam Dataset](https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv)
- Features: Message text and category labels (spam/ham)

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- NLP and TF-IDF

## Project Workflow
1. Loaded and explored the dataset.
2. Checked spam and ham class distribution.
3. Removed duplicate and missing records.
4. Preprocessed text by converting it to lowercase, removing punctuation and removing stopwords.
5. Converted text into numerical features using TF-IDF.
6. Split the dataset into training and testing sets.
7. Trained two machine learning models:
   - Multinomial Naive Bayes
   - Logistic Regression
8. Evaluated both models using accuracy, precision, recall, F1-score and confusion matrices.

## Model Evaluation
The models were evaluated using a separate test dataset.

**Add your actual accuracy, precision, recall and F1-score results here after reviewing your notebook outputs.**

## Conclusion
This project demonstrates how machine learning and NLP techniques can be used to identify spam messages. Comparing two classification models helps understand their performance and the importance of precision and recall in spam detection.

## Internship
Oasis Infobyte – Data Science Internship