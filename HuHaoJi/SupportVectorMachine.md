# 支持向量机

- [2.1 线性可分定义](#2.1)
- [2.2 问题描述](#2.2)
- [2.3 优化问题](#2.3)
- [2.4 线性不可分情况](#2.4)
- [2.5 低维到高维的映射](#2.5)
- [2.6 核函数的定义](#2.6)
- [2.7 原问题和对偶问题](#2.7)
- [2.8 转化为对偶问题](#2.8)
- [2.9 算法流程](#2.9)
- [2.10 兵王问题描述](#2.10)
- [2.11 兵王问题程序设计](#2.11)
- [2.12 兵王问题MATLAB程序](#2.12)
- [2.13 识别系统的性能度量](#2.13)
- [2.14 多类情况](#2.14)



<a name="2.1"></a>

## 2.1 线性可分定义

线性可分（Linear Separable）

线性不可分（Nonlinear Separable）

特征空间维度 ≥ 四维时 => 超平面（Hyperplane）

用数学严格定义训练样本以及它们的标签：

假设我们有N个训练样本和它们的标签


$$
{(X_1, y_1),(X_2, y_2), ..., (X_N, y_N)}
$$
其中


$$
X_i = [x_{i1},x_{i2}]^T
y_i = {+1, -1}
$$