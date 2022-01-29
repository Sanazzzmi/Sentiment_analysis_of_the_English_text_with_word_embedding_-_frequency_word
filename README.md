# Sentiment_analysis_of_the_English_text_with_word_embedding_-_frequency_word
[This article](http://acta.uni-obuda.hu/Hayashi_Fujita_94.pdf) uses Twitter datasets and movie datasets for English language.
training dataset = > [Twitter dataset](http://thinknook.com/twitter-sentiment-analysis-training-corpus-dataset-2012-09-22/)
test dataset => [sts gold weet](https://github.com/pollockj/world_mood/blob/master/sts_gold_v03/sts_gold_tweet.csv)
In this article, [wordembedding glove](https://nlp.stanford.edu/projects/glove/) used in English language.
In the final output, we have a 200-dimensional vector for each sentence Which we gave these vectors as input to xgboost classifier.
