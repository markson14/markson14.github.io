## [章子维](https://markson14.github.io/)

手机： +86-13610006539							|	邮箱：zhangzw14@outlook.com

kaggle：https://www.kaggle.com/markson14		|	github：https://github.com/markson14

---

### 教育背景

- **华南农业大学 (广东省“211“工程) 电子工程学院** 
  - 时间：2012.9 ~ 2016.6
  - 电子信息工程
- **悉尼大学 School of Computer Science **
  - 时间：2017.3 ~ 2019.5 
  - Master of Information Technology (Postgraduate) 
  - Master of Information Technology Management (Postgraduate) 

---

### 工作经历

**WiFi 万能钥匙**

时间：2019.1 ~ 2019.4

职位：图像算法工程师

- 项目一为移动端的图像识别及编解码。个人主要负责最优化部分的算法选择，测试以及调优。以及预处理中使用的机器学习分类器（基于SVM的图像二分类）。
- 项目二负责人脸识别算法的调研和工程化，最终选择基于MTCNN模型的构造，训练以及优化。

**Nuance Communication**

时间：2019.4 ～ 至今

职位：TTS Research Engineer

- 项目为TTS系统调优和模型demo网页端的落地实现。个人负责网页端实现和部分TTS后端调优。

------

### 项目经验

##### **Fine-Grained Species Classification** 

时间：2018.3 ~ 2018.6

非均衡类别的高精度图像分类。主要难点在于样本class不均衡，以及做到区分高相似度图像。在解决非均衡class问题中我们尝试过过采样和欠采样以及我们组的利用mask-rcnn与gan对已知样本的前后景进行分离与排列组合形成新的样本补充进训练集。高精度的图像分类我们主要利用了增大input size 以及max-pooling对high level feature的提取和利用global average pooling替代flatten layer进行计算量的减少的方法在保持准确率的同时提升模型运行效率。

##### **Kaggle: What’s Cooking?**

时间：2018.6 ~ 2018.9

项目是通过对菜谱分析正确分类其菜系；特征工程：通过NLTK的WordNet识别名词并且提取；将非英语单词筛去或转换成英语单词；删去仅含有一个原料的菜系剔除噪音；整合之后的菜谱原料通过TF-IDF生成词重要性参数。最后，将生成参数通过多个支持向量机的分类模型(SVC)，LBGM 和DNN 的 Voting 分类器进行分类。分类达到 82.622%的准确率，排行第 7/538。

##### **Kaggle: Forest Cover Type**

时间：2018.6 ~ 2018.9

该项目是通过对森林覆盖的各种因素来确定其类型。原数据比较松散，通过对features的整合并寻找其中规律，从而生成一部分新的features。并运用 AdaBoost 进行分类，基函数为 ExtraTreesClassifier。以及对数据的常规化。准确率达到 85.076%，排行第 3/359。

##### **Spark KNN Algorithm**

时间：2018.3 ~ 2018.4

该项目主要基于 spark 下的编写复现并行式 K nearest neighbours 来实现对 MNIST 数据集的分类。在相同 k 条件下，基于 scikit-learn 的非并行 KNN 算法对该数据分类耗时接近 5 分钟，准确率 97%;而基于 spark 下的 KNN 算法对数据分类耗时仅 87 秒，准确率 97%。

---

### 专业技能

- **Python Coding** 通过 LeetCode 训练项目的过程中训练习得，坚持每周参加Weekly Contest保持对算法的敏感度。
- **Cpp Coding** 通过图像处理实习项目以及OpenCV项目习得。
- **机器学习** 机器学习的基础模型例如逻辑回归，SVM，决策树等等，也学习过工业级别应用的xgboost，Lightgbm等集成算法。具体实现过 KNN，逻辑回归算法。最近在致力于从底层复现各种机器学习算法 [(Machine Learning from Scratch)](https://github.com/markson14/ML_fromScratch) 以更加深刻的了解算法原理。
- **深度学习** 熟悉CNN, RNN及神经网络特点与优劣，神经网络优化方法。具有深度神经网络的项目经验。主要研究方向为计算机视觉，了解自然语言处理。主要应用的深度学习框架为keras，pytorch以及tensorflow。
- **计算机视觉** 
  - 图像分类：通过项目熟悉图像分类的操作流程与神经网络的处理过程以及当下主流模型的架构及优劣。
  - 目标侦测：通过研究项目习得主流的目标检测算法如RCNN与YOLO系列，以及SOTA模型。
  - 图像分割：实例分割算法如Mask RCNN。了解实现原理，优劣及应用场景。


