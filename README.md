# disaster-tweet-classifier-nb
Employs Natural Language Processing (NLP) and Multinomial Naïve Bayes to analyze anonymous Twitter text and accurately classify whether a post describes a real emergency or a fake/misleading report.

disaster-tweet-classifier-nb/
│
├── data/
│   ├── tweets_raw.csv        # Raw tweet text and target labels (0/1)
│   └── tweets_cleaned.csv    # Stemmed and tokenized text data
├── notebooks/
│   └── nlp_eda_modeling.ipynb # Text statistics and vectorization analysis
├── src/
│   ├── text_cleaning.py      # Regex cleaning, stopword removal, and tokenization
│   └── vectorizer_nb.py      # TF-IDF vectorizer and Multinomial Naive Bayes model
├── README.md                 # System impact on emergency response operations
└── requirements.txt          # Dependencies (scikit-learn, nltk, pandas)
