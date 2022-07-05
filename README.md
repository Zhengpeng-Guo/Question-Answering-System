# Question-Answering-System

 检索式的问答系统   
 
**数据：**SQuAD2.0

**整体框架：** 基于文本相似度的FAQ问答系统，

**语义向量：** 为验证效果，分别使用了TF-IDF，GLOVE，BERT-embedding，三种词向量，使用 average pooling  的方式来表达句子的语义向量

**重排序(匹配阶段)：** 使用cosing相似度计算方式计算相似性，此外为了提升模型的性能，使用了倒排序表进行优化，同时也加入了拼写纠错的功能。
