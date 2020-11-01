# Twitter-hate-speech-detection

### Binary classification on twitter datset to label a given tweet as "hate" or "not hate"

## Preprocessing done:
- Converted to lowercase
- Removed punctuations and url
- Used WordNetLemmatizer and PorterStemmer

## Classification:
- Applied TFIDF vectorizer
- Tested on Logistic Regression, Naive Bayes, Random Forest and SVM
- Best accuracy and f1 score was achieved on SVM classifier
