# Sentiment Analysis of IMDb Movie Reviews  

Sentiment Analysis is an NLP application that identifies a text corpus’s emotional or sentimental tone or opinion. Usually, emotions or attitudes towards a topic can be positive, negative, or neutral. This makes sentiment analysis a text classification task. Examples of positive and negative expressions are:
“I enjoyed the movie!” – Positive
“It was the most terrible movie I have ever seen.” – Negative

The [IMDb moview reviews dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) sourced from Kaggle, comprises 50,000 records, half of which are positive and the other half negative. each consisting of two essential columns:  
- Review: Textual content of individual reviews.
- Sentiment: Label of each review, categorized as either "positive" or "negative.“

###🚀 Steps Followed: 

1. Getting and Loading the Dataset
2. Text Processing
3. Model Building
4. Hyperparameter Tunining
5. Model Evaluation and Comparision
6. Model Improvment


### Model Architectures
We thoroughly investigated RNN, LSTM, CNN+LSTM, and a novel hybrid framework combining CNN and Bidirectional LSTM. A comparative analysis was conducted to gauge the efficacy of each model architecture.

### 🔍 Results and Findings:

Hybrid Convolutional-BiLSTM model showcased the highest accuracy at 89%.
LSTM model achieved an accuracy of 86%.
CNN+LSTM model's performance underscored the importance of hyperparameter tuning and architectural design.
