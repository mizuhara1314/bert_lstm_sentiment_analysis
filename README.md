# bert_lstm_sentiment_analysis
基於預訓練bert模型並加入lstm層的改良，對直播間留言的情感分析
# 使用技術
transformer , pytorch

# 成果
bert_base:訓練集(99%)
bert_lstm:訓練集(99.22%)
# 踩坑經驗
本來是先進行jieba分詞並使用keras的token來建立詞向量，但這會與之後導入預訓練bert模型會衝突，BERT 使用的中文分詞是 WordPiece 分词器，
所以得用bert_chinese_base的token分詞器才能在訓練過程中讓bert讀懂
# 功能擴展
之後再會是我的直播間情緒分析預測網站其中一個模塊

# 模型下載


