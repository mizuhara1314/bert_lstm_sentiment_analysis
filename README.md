# bert_lstm_sentiment_analysis
基於預訓練bert模型並加入lstm層的改良，對直播間留言的情感分析，可以自行把訓練集換成繁體產生繁體專用模型

更新:目前colab上的notebook都無法在github上檢閱，請自行下載即可

# 使用技術
transformer , pytorch

# 成果

<img width="980" height="773" alt="image" src="https://github.com/user-attachments/assets/6057bf25-8aea-44dc-a20b-7d22e865545c" />

<img width="928" height="414" alt="image" src="https://github.com/user-attachments/assets/5cd3a008-8eaf-4ce4-a268-4d4ae2ae7f31" />

# 踩坑經驗
本來是先進行jieba分詞並使用keras的token來建立詞向量，但這會與之後導入預訓練bert模型會衝突，BERT 使用的中文分詞是 WordPiece 分词器，
所以得用bert_chinese_base的token分詞器才能在訓練過程中讓bert讀懂
# 功能擴展
之後會是我的直播間情緒分析網站其中一個模塊

# 模型下載

https://drive.google.com/file/d/1lnJuSLQKl6Xi-o9SYQ3hwElazgswvjKf/view?usp=sharing
