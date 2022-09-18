# 油气人工智能基础<br />
---
# 聚类算法<br />
## 划分聚类 — K-means<br />
定义：K-means算法是通过**均值**进行数据点的聚类，而且是以**距离**作为数据集样本相似性的指标，我在编写的时候采用的是欧式距离.由于是随机生成初始聚类点，所以初始点的生成会影响聚类结果.<br />
## 层次聚类 — Agnes(AGglomerative NESting)<br />
定义：它先将数据集的每个样本看作是一个初始簇，然后在算法中运行的每一步找出**距离最近**的两个簇进行合并，该过程持续进行，知道达到预设的聚类簇的个数<br />
## 模型聚类 — GMM(Gaussian Mixture Model)<br />
定义：涉及**EM**算法以及**多维高斯分布**，算法原理还没太搞懂.<br />
## 密度聚类 — DBSCAN(Density-Based Spatial Clustering of Applications with Noise)<br />
定义：密度聚类算法从样本的密度角度来考虑样本之间的可连接性，并给予可连接样本不断拓展其聚类簇的大小并最终获得结果，DBSCAN算法不需要提前设定聚类数k，其通过“邻域参数”( $\epsilon$ , $MinPts$ )来刻画样本分布的紧密程度<br />

---
# 特征提取算法<br />
## 主成分分析 — PCA<br />
定义：PCA(Principal Component Analysis),即主成分分析,是一种统计学方法.通过正交变换将数据转化到新的坐标基中，从而将原本可能的变量投影转换为线性无关的变量.如果变换后的维度小于变换前的维度，就可以对数据进行压缩，达到降维的效果<br />
## 核主成分分析 — KPCA<br />
定义：核主成分分析 (KPCA) 是一种非线性数据处理方法，其核心思想是通过一个非线性映射把原始空间的数据投影到高维特征空间， 然后在高维特征空间中进行基于主成分分析 (PCA) 的数据处理。<br />
## 线性判别分析 — LDA<br />
定义：LDA算法的目标是使降维后的数据类内方差最小，类间方差最大（即使数据在低维度上进行投影，投影后希望每一种类别数据的投影点尽可能的接近，而不同类别的数据中心之间的距离尽可能的大。<br />
## 核Fisher判别分析 — KFD<br />
定义：<br />

---
# 常用的分类方法<br />
## K近邻方法 — K-nearest-neighbor<br />
定义：KNN(K-nearest-neighbor)<br />
## 朴素贝叶斯<br />
定义：朴素贝叶斯法（Naive Bayes model）是基于贝叶斯定理与特征条件独立假设的分类方法,朴素贝叶斯方法是在贝叶斯算法的基础上进行了相应的简化，即假定给定目标值时属性之间相互条件独立。也就是说没有哪个属性变量对于决策结果来说占有着较大的比重，也没有哪个属性变量对于决策结果占有着较小的比重。虽然这个简化方式在一定程度上降低了贝叶斯分类算法的分类效果，但是在实际的应用场景中，极大地简化了贝叶斯方法的复杂性。<br />
## 逻辑回归<br />
定义：逻辑回归也称作logistic回归分析，是一种广义的线性回归分析模型，属于机器学习中的监督学习。其推导过程与计算方式类似于回归的过程，但实际上主要是用来解决二分类问题（也可以解决多分类问题）。通过给定的n组数据（训练集）来训练模型，并在训练结束后对给定的一组或多组数据（测试集）进行分类。其中每一组数据都是由p 个指标构成。<br />

---
# 集成学习算法<br />
## Bagging集成学习算法 - 随机森林<br />
定义：<br />
## Boosting集成学习算法<br />
定义：<br />

---
