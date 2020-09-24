# text-summarizer

The code above uses networkx, nltk and numpy libraries in python to summarize a text.
the code is initially divided in individual sentences.
then the stemmed words are exracted removing the stopwords.
sentence words are vectorized. Cosine similarity is found between them.
Using the page ran method, we figure out the lines we require.
We choose the number of lines required to be extracted and we call the function.
