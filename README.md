# mailContent_Analysis
# 目前分成四個部分來取nodes及edges的keywords，分別是：

1）only remove stopword and counting without tfidf
2）remove stopword + tf-idf
3）only counting term fequency + POS without tfidf
4）POS + TD-IDF

pos tag使用了nltk的pos_tag套件，目前只留下名詞(包含"NN")及動詞("VB")

計算nodes (only remove stopword and counting without tfidf)<br>
http://140.120.13.242:8888/notebooks/MailContent_Analysis/yun/%5B%20Nodes%20%5D%20Stopwords_only.ipynb

計算nodes (remove stopword + tf-idf)<br>
http://140.120.13.242:8888/notebooks/MailContent_Analysis/yun/%5B%20Nodes%20%5DStopwords%2BTFIDF.ipynb

計算nodes (only counting term fequency + POS without tfidf)
http://140.120.13.244:12444/notebooks/yun/%5B%20Nodes%20%5D%20Pos_tag_only.ipynb

計算nodes (POS + TD-IDF)
http://140.120.13.244:12444/notebooks/yun/%5B%20Nodes%20%5D%20Pos_tag%2BTFIDF.ipynb

計算edge tf-idf<br>
http://140.120.13.244:12444/notebooks/binhong/%5BEdge%5D%20stopword%20%2B%20TFIDF.ipynb

計算edge (only counting term fequency + POS without tfidf)<br>
http://140.120.13.242:8888/notebooks/MailContent_Analysis/ForTeacher/edge%20counting%20(only%20remove%20stopword).ipynb

計算edge (POS + TD-IDF)<br>
http://140.120.13.244:12444/notebooks/binhong/%5BEdge%5D%20stopword%20%2B%20POS%20%2B%20TFIDF.ipynb

