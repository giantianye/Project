# 推特的情感分析
* 对收集到的Twitter推文数据，通过数据清洗，例如去掉网页链接，话题标记等；
* 对所得到的数据进行分词以及词性标注，使用的库是NLTK；
* 通过构建 TF-IDF+Word2Vec 词向量模型计算所得数据和语料库的相似度；
* 利用LSTM模型对Embedding进行训练，并Dropout防止过拟合，准确率达到 86%；
