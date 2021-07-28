# Spam-Detection-using-Multinomial-Naive-Bayes-Classifier
- Any message wether spam or ham is text data which is in unstructured format
- Used TFIDF word embedding technique to convert text data (unstructured data) to structured data, with it's advantage that it gives higher weightage to important rare words and lesser weightage to unimportant frequent words with respect to the whole corpus.
- TF(term t) = No. of times term (t) occured in particular given doc./ Total no. of words in that particular given doc = (r/w). It is basically count vectorizer.
- IDF(term t) = loge(total no. of doc./ (1 + no. of doc. containing term (t)))= loge(N/1 + n). it gives higher weightage to important rare words and lesser weightage to unimportant frequent words with respect to the whole corpus.
- TFIDF matrix = TF * IDF
- Using TFIDF matrix built Multinomial Naive Bayes (used when features have discrete values) to predict whether the given message is spam or ham
