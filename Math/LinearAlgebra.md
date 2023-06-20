# 线性代数
## Content
- BASIC INTRODUCTION
- 协方差矩阵

<br>

------
## BASIC INTRODUCTION
向量：方向 & 长度   
normalization 单位化，表示方向  

dot点乘，映射到一个数；单位向量点乘得到 cos夹角
- 用于 **求夹角 以及 向量的投影**  
- 可以衡量两个方向是否接近，是否相互远离、方向是否相反  
- 可以计算关于 “前后（forward/backward）” 的信息

cross叉乘，映射到另一个向量，和原本的两个向量垂直
- 用于建立坐标系
- 可以判断 “左/右”
- 可以判断 （三角形）“内/外”（一个点在三条边向量的同侧时，在内部）

右手系`X x Y = Z` ，左手系`X x Y = -Z`  

矩阵表示变换  
（m*n矩阵 结果属于m维 作用于n维上的向量）  
<br>

---

## 协方差矩阵
获取 <b>数据中的主要成分</b>  
相关性分析（Correlation Analysis）旨在确定变量之间的共性  
协方差测量两个变量之间的方差  
假设有一个数据集，包含三个特征，分别为 x、y 和 z。计算协方差矩阵将产生一个 3 x 3 的矩阵。该矩阵包含<b>每个特征与所有其他特征及其本身的协方差</b>

<br>