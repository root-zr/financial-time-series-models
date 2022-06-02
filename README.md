# financial-time-series

#### 介绍
这个项目主要是使用Tensorflow 2.x，搭建了多种模型对5年期的国债数据进行了预测，分为连续型的预测（回归）和离散型的预测（分类）两部分。

#### 目录说明
checkpoint/
data/                                                # 数据目录，主要包括原始数据和生成的中间数据
logs/ 
img/ 
cnn.ipynb                                        #  conv1卷积神经网络目录    
lstm.ipynb                                       #  lstm神经网络目录
cnn-lstm.ipynb                               # cnn-lstm神经网络目录
arma.ipynb                                     # arma模型目录
feature_engineer.ipynb                 # 常用的金融时间序列特征工程挖掘方法目录
shibor数据获取.ipynb                   # shibor目录
 for_paper.ipynb                            # 该目录下主要有一个将多张图片合成为一张图片的代码
金融时间序列特征分析.ipynb     #  该目录主要对金融时间序列进行了分析

#### 参考

* 用滑动窗口搭建神经网络的代码主要参考自北京大学曹健老师慕课Tensorflow笔记
* 金融时间序列特征分析.ipynb 所有代码几乎全部来自https://www.heywhale.com/mw/project/5f914ae1e200680030f4452e/

* https://www.statsmodels.org/v0.12.0/index.html
* https://tensorflow.google.cn/guide/keras/functional?hl=zh_cn
* https://otexts.com/fppcn/what-can-be-forecast.html
* https://machinelearningmastery.com/cnn-long-short-term-memory-networks/
* http://colah.github.io/posts/2015-08-Understanding-LSTMs/
* https://karpathy.github.io/2015/05/21/rnn-effectiveness/
* https://keras.io/zh/examples/imdb_cnn_lstm/