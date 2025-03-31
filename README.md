The following repo talks about the Nature Language Processing(NLP) techniques from basic to advanced. 

There are multiple techiniques for 
A) data preprocessing implemented(nltk)

1. Stemmimg : conversion of word to their stem form (for eg : running : run, honesty : honest etc) using porterStem
2. Lemmatization : conversion of word to their stem form (for eg : running : run, honesty : honest, better : good etc) using WordNetLemmatizer

B) Process of converting word to vector 

1. TF-IDF (Term Frequency - Inverse Document Frequency) : TF-IDF measures word relevance by considering both word frequency within a document and its rarity across all documents.
2. N-grams : N-grams capture word sequences (e.g., bigrams: "I am", "am happy") to understand word relationships and context.
3. Bag of Words (BoW) : BoW converts text into a vector based on word frequency, ignoring word order and grammar.
4. Word2Vec: Word2Vec uses neural networks to map words to vectors, capturing semantic relationships, with words having similar meanings being close in the vector space.

Please note : used spam.csv for BOW , N-grams, TF-IDF


Additional projects added(huggingfface): 
1. Sentiment_analysis : DataSet : IMDB movie reviews, pretrained model : distilbert-base-uncased-finetuned-sst-2-english, pipeline : "sentiment"
2. text summarisation : dataset : random new artcile on AI , pretrained model : facebook/bart-large-cnn, pipeline : "summarisation"
