# Scenario-based-Problems
#  Resume Job Category Classifier using spaCy & Scikit-Learn

This project demonstrates a simple yet effective NLP pipeline to classify job categories  
(e.g., Software Developer, Data Scientist, Marketing) based on resume snippets using Python, spaCy, and scikit-learn.

---

##  Project Overview

This notebook performs the following steps:

1. **Synthetic Dataset Creation** – 30 resume text samples manually labeled into 3 job categories.  
2. **Text Preprocessing** – Tokenization, lemmatization, and removal of stop words using spaCy.  
3. **Vectorization** – TF-IDF vectorization of the preprocessed text.  
4. **Model Training** – Classification using Logistic Regression (or switchable to Naive Bayes).  
5. **Evaluation** – Accuracy check on test data.

---

## 🔧 Requirements

Install all dependencies using:

```bash
pip install spacy scikit-learn pandas
python -m spacy download en_core_web_sm
```
## Sample Output
```bash
Predicted Categories: ['Software Developer' 'Software Developer' 'Data Scientist' 'Software Developer' 'Marketing' 'Software Developer']
Actual Categories:    ['Software Developer' 'Marketing' 'Software Developer' 'Data Scientist' 'Marketing' 'Data Scientist']
Accuracy Score:       0.333...
```

