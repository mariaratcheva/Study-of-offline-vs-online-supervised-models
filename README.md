# Study-of-offline-vs-online-supervised-models

## Abstract
The goal of our project was to study and compare offline and online models in particular when using the Room Occupancy and NBA time series datasets. To this end, we implemented online and offline versions of classic Machine Learning (ML) algorithms to determine the advantages of each style of learning using performance metrics and computational costs as our primary method of evaluation. We also briefly explored applying an LSTM neural network and the Facebook Prophet forecasting package to the datasets in order to obtain examples of what the advantage of using deep learning is and what is done in industry. Finally we selected the best model for each dataset, both offline and online.

## Introduction

For this project we chose to work and study data streams. Data streams create dynamic datasets which are a particularly interesting challenge because data is continuously being generated and introduced which makes it difficult if not impossible to train a model ahead of time. Therefore, the approach taken with data streams is to apply online learning, where a model is continually trained on the new incoming data points and is able to make predictions at any point. \
Based on readings [1,2,3,4,5], we determined that the goal of our project would be studying offline ML models vs online ML models. That is to say, we chose several classic ML algorithms and built an offline model for it (i.e. letting the dataset remain static) and then also built an online model (i.e. building a model that can handle a simulated data stream as input). We then analysed the respective models based on traditional evaluation metrics and, on occasion, experimented and implemented other models and techniques to help improve performance. Some investigations done parallel to our primary project involved exploration of data balancing techniques, industry forecasting regression models such as Facebook Prophet, implementing bagging and boosting algorithms and doing a brief foray into deep learning by implementing an LSTM classifier. These parallel investigations were done in the hopes of better understanding how to create an optimal online classifier. \
By the end of this semester-long project, we hoped to learn the advantages and disadvantages of online learning and determine what is the optimal ML algorithm to tackle a data stream with and the best implementation techniques to employ.

## References

[1] Erfan Aasi, Cristian Ioan Vasile, Mahroo Bahreinian, and Calin Belta. Classification of time-series data using boosted
decision trees. arXiv preprint arXiv:2110.00581, 2021. 1

[2] Albert Bifet and Ricard Gavalda. Learning from time-changing data with adaptive windowing. In Proceedings of the 2007 SIAM international conference on data mining, pages 443–448. SIAM, 2007. 1

[3] Christopher M Bishop. Pattern recognition and machine learning. springer, 2006. 1

[4] Heitor Murilo Gomes, Jean Paul Barddal, Luis Eduardo Boiko Ferreira, and Albert Bifet. Adaptive random forests for data stream regression. In ESANN, 2018. 1

[5] Jacob Montiel. Learning from evolving data streams. mental, 2018. 1

