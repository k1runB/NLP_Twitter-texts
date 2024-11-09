# NLP_Twitter-texts

Dataset Description :
DatasetLink https://www.kaggle.com/datasets/nelgiriyewithana/emotions
Each entry in this dataset consists of a text segment representing a Twitter message and a
corresponding label indicating the predominant emotion conveyed. The emotions are classified
into six categories: sadness (0), joy (1), love (2), anger (3), fear (4), and surprise (5). Whether
you're interested in sentiment analysis, emotion classification, or text mining, this dataset
provides a rich foundation for exploring the nuanced emotional landscape within the realm of
social media.

Dataset imbalance :
We tackled the slight class imbalance present in our dataset directly within our model's
architecture or training process. This could involve techniques such as adjusting class weights,
oversampling minority classes, or undersampling majority classes during training to ensure that
the model learns effectively from all classes regardless of their imbalance. By incorporating
these strategies within the model itself, we aim to mitigate the impact of class imbalance on the
model's performance without explicitly modifying the dataset.

Work done:
Project focuses on sentiment analysis using XGBoost, a powerful gradient boosting
algorithm. We preprocess text data and extract features for training the model. Through
experiments and analysis, we evaluate XGBoost's performance in sentiment classification tasks
and compare it with other algorithms like SVM and LSTM. Our findings contribute to enhancing
sentiment analysis research and offer practical insights for implementing sentiment analysis
solutions across domains
