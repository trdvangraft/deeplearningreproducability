# Deep learning reproducability project

In the past couple of weeks I got intrigued by the results achieved in the following paper [Deep Learning-Based Multivariate Probabilistic Forecasting for Short-Term Scheduling in Power Markets](https://ieeexplore.ieee.org/document/8464297). Unfortunatly the code of this paper was not published, the architecture of the network is unknown and the data augementation is only vagually described.

I therefore set out to reproduce the results that are published in this paper by creating my own AI that can forecast the day ahead prices of the Belgium energy market, while sticking as closely as possible to the original paper.

In my [blog](https://tijmengraft.medium.com/deep-learning-based-multivariate-probabilistic-forecasting-for-short-term-scheduling-in-power-b71ac9a750d8) I discuss the entire process in detail. This repository contains the necessary code in order to achieve the same results. The code has been writtin in Colab to get easy accessability.

## The data
The data has been made available in the `forecasting` folder. This data should be copied to your local drive and put in the correct path as specified by the code.
