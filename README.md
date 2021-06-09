# TF-IDF News Analysis
 Codecademy term frequency-inverse document frequency(TF-IDF) natural language processing project.

The articles are provided by Codecademy, based on a selection of articles from a Kaggle dataset.

The project compares using the TFIDFTransformer and TFIDFVectorizor.  The vectorizor will word count and analyse the pre-processed text directly, whereas the transformer requires prior application of a countvectorizor.  

The articles are preprocessed using the nltk library.  Text is cleaned, tokenized, normalised, and parts of speech identified.  

Word counts are then performed on each article with nltk's countvectorizor. TFIDFTransformer is then applied to convert each wordcount into a score for each article.

TFIDFVectorizer is then applied to the preprocessed text to see the tf-idf score for each article.

The scores are then compared to evaluate these methods.

Finally, the word with the highest score for each article is returned to identify the prevailing topic.  



