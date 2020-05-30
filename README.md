# toxic-comment-classificationNLP

The project aims to build a multi-headed model that’s capable of detecting different types of toxicity. This model classifies a given comment into labels 'toxic', 'severe_toxic', 'obscene', 'threat', 'insult', 'identity_hate'. I have taken the dataset of comments from Wikipedia’s talk page edits, collected by Kaggle. 

Dataset consists of 1,59,571 rows having columns as – ‘id’, ‘comment_text’, 'toxic', 'severe_toxic', 'obscene', 'threat', 'insult’ and 'identity_hate'.

### Concept of NLP Pipeline is used in building the model – 
Raw Text --> Tokenization --> Text Cleaning (Removing punctuations and stop words) --> Vectorization (TF-IDF vectorizer) --> ML Algorithm (Logistic Regression in this case) --> Toxic Comment Classifier
