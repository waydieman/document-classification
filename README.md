# document-classification
document classificaation based on deep convolutional recurrent neural networks
  
  由於深度學習的崛起，所以本文嘗試藉由資料集20 newsgroups dataset，在
Scikit-learn 和 Keras的框架下，透過機器學習和深度學習的手法，進行電腦的模擬，我們看見了經由機器學習與深度學習不同手法，作用在文本分類上得到不同的準確度 (accuracy)，利用深度學習的方法 準 確度甚至高達 96%。
  
  在機器學習上我們利用Naive Bayes classifier，SVM(Support Vector Machines) classifier，Logistic Regression classifier，RandomForest classifier，，……..等等模型進行文本分類，並執行量測準確度。
  
  深度學習上我們搭建神經網路， Fully Connect Neural Network LSTM(Long short-term memory) Neural Network BiLSTM(Bidirectional Long short-term memory) Neural Network CNN(Convolutional Neural CNN_LSTM Neural Network
LSTM_CNN CNN_ BiLSTM Neural Network BiLSTM_CNN等模型，並使用預先訓練的詞向量崁入神經網路，這裡的詞向量我們使用 Glove6b Word2vec fastText等模型建立的詞向量，並且進行文本分類及準確度的量測。

  我們也發現神經網路模型能夠實現卓越的文本分類，特別是卷積神經網路(CNN)，及 具記憶的遞歸 神經網路 (LSTM)這兩種主流架構，我們也結合這兩種架構的優勢， 提出了文本分類基於深度卷積遞歸神經網路模型 。
利用卷積 (CNN)來抽取更高級別的短語，及將短語送進 具記憶的遞歸神經網路(LSTM)中獲得全局句子的表示。或者是利用 LSTM來獲取全局句子的表示，在送進 CNN中抽取更高級的短語。 我們評估提出的架構在文本分類任務上 。
  實驗表明深度卷積具雙向記憶的遞歸神經網路(CNN_ BiLSTM)這個模型 優於文本分類上 其它模型的 實驗結果，我們得到接近 96%的準確度。
同時我們也歸納了特徵圖Feature Maps和最大池化 Max pooling輸出的遞迴關係式 。
