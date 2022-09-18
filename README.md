# Emotions-Classification-from-Tweets

Used BERT language model from transformers library by hugging face to classify 13 emotions from 40,000 tweets. The dataset was found on Kaggle [here.](https://www.kaggle.com/datasets/pashupatigupta/emotion-detection-from-text)

Tokenization and Embedding were handled by BERT model, training took a lot of time even for one epoch but the results are astonisngly brilliant. Dataset was imbalanced and there was skewness. Model might have performed a lot better if I handled both skewness and imbalance but I chose not to because BERT model is pre trained by Google and it is known to work pretty well even on small datasets.
