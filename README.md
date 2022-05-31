# binaryClass

**基于医学数据的二分类问题，参考**

https://mp.weixin.qq.com/s/JaDCbYVuQe1Jkx6UJST3mg



### 一、数据集

train.xlsx 和 test.xlsx 含有缺失值

train1.xlsx 和 test1.xlsx 无缺失值



### 二、模型选择

经典模型

神经网络模型（ tf.keras.Sequential()）



### 三、实验结果

`众数填充，PCA降维、向下采样，参数寻优`

模型XGBoost效果最好, 模型效果如下图所示

模型XGBoost: Acc值为0.80   AUC值为0.61

其他的模型："AdaBoost", "LogisticRegression","Nearest Neighbors", "Linear SVM", "RBF SVM", "Gaussian Process", "MLP"效果差一点



