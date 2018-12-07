# M9：[深度分析](https://github.com/OS-Q/M9) 

[![sites](OS-Q/OS-Q.png)](http://www.OS-Q.com)

#### 归属边缘计算：[Q3](https://github.com/OS-Q/Q3)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M9/wiki) 

M9深度分析节点，用于部署深度学习模型，实现边缘深度加速

### [共用资源](https://github.com/OS-Q/M9/wiki/) 




---

边缘设备命名规则：体系 Q[1,4] > 节点 M[1,12] > 平台 W[1,52] > 设备 D[1,365]。

## [包含平台](https://github.com/OS-Q/M9/wiki/) 

#### W36：[tensorflow](https://github.com/OS-Q/W36)

核心代码和Caffe一样是用C++编写的,能够基于ARM架构编译和优化

#### W37：[caffe](https://github.com/OS-Q/W37)

Caffe的一大优势是拥有大量的训练好的经典模型（AlexNet、VGG、Inception）乃至其他state-of-the-art（ResNet等）模型，在计算机视觉领域Caffe应用尤其多

#### W38：[MXNet](https://github.com/OS-Q/W38)

开源的、轻量级、可移植的、灵活的深度学习库，它让用户可以混合使用符号编程模式和指令式编程模式来最大化效率和灵活性，目前已经是AWS官方推荐的深度学习框架。

#### W39：[Keras](https://github.com/OS-Q/W39)

Keras是一个崇尚极简、高度模块化的神经网络库，基于Theano的一个深度学习框架，它的设计参考了Torch，用Python语言编写，是一个高度模块化的神经网络库，支持GPU和CPU，并可以同时运行在TensorFlow和Theano上。

## [同级节点](https://github.com/OS-Q/Q3/wiki/)

#### M7：[系统管理](https://github.com/OS-Q/M7)

用于管理Q系统各个节点，常态维护和异常处理
 
#### M8：[数据处理](https://github.com/OS-Q/M8) 

用于实现特定算法的计算功能

#### -> M9：[深度分析](https://github.com/OS-Q/M9)

用于部署相关深度模型扩展边缘计算功能

---
###  qitas@qitas.cn

###  [Q redefined the scope of Operation System](http://www.OS-Q.com)

####  2018-12-7

