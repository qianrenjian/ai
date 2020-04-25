# AI related articles and samples

The goal of this reposistory is to summarize the AI technologies and implementations.

## The components of the repository

### Datasets


### Articles and samples
  The documents for the AI articles are mainly written using markdown format, for easily demostrating the examples, we use docker to setup pytorch, jupyter notebook and other libraries environments. please refer to [INSTASLL](./docs/deep_learning/pytorch/manual.md) for the preparation of the environments setup.

#### Math
- [Linear Algebra Review and Reference(1)](http://note.youdao.com/noteshare?id=b7a6cfe77e3906bdb5639d1acec3c88c)
- [Linear Algebra Review and Reference(2)](http://note.youdao.com/noteshare?id=a3dda151febf0da4dc17df5ec918b41b)
- [Entropy_Cross_Entropy_KL_Divergence](http://note.youdao.com/noteshare?id=b996997b7918d6c3fb9f6aa6813aa675)
- [Taylor_expansion_Multi_Variables_Functions_extremum](http://note.youdao.com/noteshare?id=951f44d73e0777672abffc7ef891f2ea)

#### Machine Learning
|              Topic         |          sub section or code        |
|------------------------------|-------------------------------------|
|[Linear_Regression](http://note.youdao.com/noteshare?id=e3d052b17e33e6a1d9c45b7f8a90d86c/)| [code](https://github.com/kindlytree/ai/blob/master/samples/ml/linear_regression.ipynb)|
|[Logistic_Regression](http://note.youdao.com/noteshare?id=a62bb63c6a049ce5e0cdc8abfe8ba3fd)| [code](https://github.com/kindlytree/ai/blob/master/samples/ml/logistic_regression.ipynb)|
|[Newton's Method](http://note.youdao.com/noteshare?id=57e9b323d4ae19c215c421fcac32b638)|[code](https://github.com/kindlytree/ai/blob/master/samples/ml/newton_method.ipynb)|
|[Generalized Linear Models](http://note.youdao.com/noteshare?id=b814a849cf4752746518d4f63ef0d79c)|[softmax regression code](https://github.com/kindlytree/ai/blob/master/samples/ml/softmax_regression.ipynb)|
|[Generative Learning algorithms](http://note.youdao.com/noteshare?id=179205e43731362a960bf52236599fa9)| |
|[Gaussian discriminant analysis](http://note.youdao.com/noteshare?id=7a34e72665581d2d379ac9a9cdebd0ce) | |
|[Naive Bayes](http://note.youdao.com/noteshare?id=0ca8c256d4dcb349dd32b155594426ea) | |
|[Kernel Methods](http://note.youdao.com/noteshare?id=5de8fb8eaa20e53517671b7d706bd6c6) | |
|[SVM](http://note.youdao.com/noteshare?id=04eb156cc9eb0137844a2a381f3f1668) | |
|[Learning Theory](https://note.youdao.com/ynoteshare1/index.html?id=85c244e8f122dc38842208d7c6f0bfe4&type=note) | |
|Adaboost |[算法原理及推导](https://www.cnblogs.com/liuwu265/p/4692347.html) |
|[Decision Tree](https://blog.csdn.net/jiaoyangwm/article/details/79525237) | |
|[Random Forest](https://blog.csdn.net/weixin_41940752/article/details/98717868) | |
|Tree Boosting |[CART回归树](http://note.youdao.com/noteshare?id=922bd61daea279fed55ac3359c4f9cd3)  <br> GBDT <br> [XGBoost](https://blog.csdn.net/u014411730/article/details/78796890)<br> LightGBM|
|PGM| HMM MRF|
|Neural Networks|[Back Propagation](http://ufldl.stanford.edu/tutorial/supervised/MultiLayerNeuralNetworks/) |
|The k-means clustering algorithm | |
|Mixtures of Gaussians and the EM algorithm |[GMM](http://note.youdao.com/noteshare?id=611be89d2eeb9c40c79bc5f5e86bc022) <br> [The EM algorithm](https://www.cnblogs.com/bigmoyan/p/4550375.html)|
|Factor analysis| |
|Principal components analysis|[PCA](https://blog.csdn.net/program_developer/article/details/80632779) |
|Independent Components Analysis| |
|Reinforcement Learning and Control| [MDP](https://blog.csdn.net/unixtch/article/details/78922936) |

#### Deep Learning
- References
  - [斯坦福网络文字版课程](http://ufldl.stanford.edu/tutorial/)
- CNN
- RNN
    - LSTM
        - [公式及实现](http://note.youdao.com/noteshare?id=84b5e5bad8db62a45682c5b928a4e9a8&sub=5708D04E282940B3922FAA10C096CBE8)
- GAN
- VAE

#### pytorch samples
- (强烈推荐)[pytorch入门与实践](https://github.com/chenyuntc/pytorch-book)
- [PyTorchDocs](https://github.com/fendouai/PyTorchDocs)

### Papers and related code
- [cvpr](https://github.com/Sophia-11/Awesome-CVPR-Paper)
- [CVPR2020](https://github.com/extreme-assistant/CVPR2020-Paper-Code-Interpretation/blob/master/CVPR2020.md)
- [ICCV 2019](https://github.com/extreme-assistant/iccv2019)

## References
- [stanford course](http://cs229.stanford.edu/syllabus.html)
- [ufldl](http://ufldl.stanford.edu/wiki/index.php/UFLDL_Tutorial)/(http://ufldl.stanford.edu/tutorial/)
- [AndrewNg 机器学习笔记](https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes/tree/master/markdown)
- [微软AI课程](https://github.com/microsoft/ai-edu)
- [哥伦比亚大学 应用机器学习](https://www.cs.columbia.edu/~amueller/comsw4995s20/schedule/)
- [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)

## FAQ
- How to setup local environment for python notebook?
  - please refer [notebook setup](./docs/deep_learning/pytorch/manual.md) to setup up the environment
  
| topic |
|-------|
|[SVM和LR的区别和联系](https://blog.csdn.net/qq_35945399/article/details/81175772)|
|[分类器模型评价指标](https://blog.csdn.net/guohecang/article/details/52276548)|
|[sigmoid和relu的优缺点](https://blog.csdn.net/u011684265/article/details/78039280)|

## TODO items
- [ ] cs229 articles and samples preparation
- [ ] most popular applications introduction
- [ ] kaggle samples preparation

