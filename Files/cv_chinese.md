## [章子维](https://markson14.github.io/)

手机： +86-13610006539							|	邮箱：zhangzw14@outlook.com

kaggle：https://www.kaggle.com/markson14		|	github：https://github.com/markson14

---

### 工作方向：算法工程师

目前就职于九章云极(ZetYun)并担任数据科学家一职，主要负责前沿计算机视觉算法的调研，研发及落地工作如人脸识别，情绪识别，缺陷检测等。业余兴趣爱好喜欢参加kaggle比赛。

---

### 工作经历

#### 九章云极 

时间：2019.6 ~ 至今

职位：数据科学家

**浦发数字人深度学习实验室**

该项目主要结合各项AI技术创造出来的一个虚拟数字人用于银行线下金融产品推荐业务。个人主要负责该项目中图像算法相关的研发

1. 人脸识别：该项目中人脸追踪的底层plugin开发。弱认证阶段主要用到了RetinaFace网络对人脸边框的定位以及五个关键点的定位，强认证阶段在后续接上mobilenet0.25+arcface的神经网络用作人脸识别。 由于项目部署在基于C和C++的框架上，整个pipeline均使用C++开发并最后集成在gsteamer plugin内。网络通过TVM进行模型计算图优化使得整个推理过程达到实时效果。
2. 人像合成：该项目中在业务流结束时与数字人合影的功能。首先需要定位人像的位置，再通过mask-rcnn模型抠出人像并通过背景虚化后将处理过后的图片与数字人背景图片合成。
3. 情绪识别：在人脸识别的pipeline添加自定义vgg情绪识别模型。图像训练集FER2013，ExpW先通过人脸侦测确定面部位置后抠出作为训练图片。清理过后的数据集相较于原始数据集有2.3%的提升，合并的数据集训练结果单模型达到SOTA结果。

**宁德时代生产线缺陷检测项目**

该项目主要基于APS平台运用目标侦测和图像分类网络识别出生产线上具有缺陷的材料模块并在后续将其筛选出销毁。个人主要负责分类与侦测网络算子的开发。整个pipeline设计运用先侦测后分类的两阶段流程，首先运用yolov3侦测出缺陷模块，而后将bbox内图片传送至resnet分类网络做进一步分类。该设计相比于单模型能够提升缺陷检测的召回率和准确率。



#### WiFi 万能钥匙

时间：2019.1 ~ 2019.4

职位：图像算法工程师

项目主要为移动端的图像识别及编解码。个人主要负责最优化部分的算法选择，测试以及调优。以及预处理中使用的机器学习分类器（基于SVM的图像二分类）。目前负责人脸识别算法的调研和工程化。

---

### 项目经验

#### **[Kaggle] Understanding Clouds from Satellite Images **

时间：2019.11 ~ 2019.11

基于卫星图拍摄的云层确定云层种类以分辨气候变化。整个pipeline的设计大概是先通过分类网络移除一部分false postive，然后在使用EfficientB4作为Encoder和FPN与UNet作为Decoder的ensemble model结合label smoothing来训练出比较鲁棒的模型。在模型预测的时候，通过Test Time Augmentation来显著提升模型的预测效果。最终获得65/1538 银牌成绩。



#### **Fine-Grained Species Classification** 

时间：2018.3 ~ 2018.6

非均衡类别的高精度图像分类。主要难点在于样本class不均衡，以及做到区分高相似度图像。在解决非均衡class问题中我们尝试过过采样和欠采样以及我们组的利用mask-rcnn与gan对已知样本的前后景进行分离与排列组合形成新的样本补充进训练集。高精度的图像分类我们主要利用了增大input size 以及max-pooling对high level feature的提取和利用global average pooling替代flatten layer进行计算量的减少的方法在保持准确率的同时提升模型运行效率。

---

### 教育背景

- **华南农业大学 (广东省“211“工程) 电子工程学院** 
  - 时间：2012.9 ~ 2016.6
  - 电子信息工程
- **悉尼大学 School of Computer Science **
  - 时间：2017.3 ~ 2019.5 
  - Master of Information Technology
  - Master of Information Technology Management

---

### 专业技能

- 计算机视觉：图像识别，目标检测，目标分割，人脸识别
- 编程开发：C++，Python
- 深度学习框架：Pytorch, MXNet, TensorFlow