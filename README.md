# CNN-RNN-NLP
# [(1dCNN, 1dRNN) + NLP Project OverView](https://github.com/FrankDTS/CNN-RNN-NLP/blob/main/CNN%2CRNN%2BNLP.ipynb)
 * Built several Machine Learning models (NLP) and Neural Network models (CNN, RNN) to predict types of meals do people eat base on foods name
 * Built Feature Engineering methods to give data new feature.

# Code and Resourced Used
  * Python 3.8
  * Packages: pandas, numpy, seaborn, matplotlib, sklearn, Xgboost, nltk, re, keras, tensorflow
  * [Method] (https://zhuanlan.zhihu.com/p/62077601)
  * [Embedding] (https://www.zhihu.com/question/45027109)
  
# Data Preprocessing
  1. Built function to remove all the words after ',' and '-' since most of they are food weight unit
  2. one-hot encoding for y (label)
  3. Combine food name and brand_name together, convert them to interger sequence
  ![string to int](https://github.com/FrankDTS/CNN-RNN-NLP/blob/main/image/Screen%20Shot%202021-05-10%20at%209.43.39%20PM.png)

# Fit and Predict models
  1. NLP with XGboost classifier
  2. CNN(1d)
  3. RNN(1d)
