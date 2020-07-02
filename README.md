### KNN_MNIST
### 计算机科学与技术201804班闫锐  U201814607
##### 步骤1  处理文本，将图像转换为向量
##### 步骤2  计算测试对象到训练集中每个对象的距离，按照距离的远近排序
##### 步骤3  选取与当前测试对象最近的K的训练对象，作为该测试对象的邻居
##### 步骤4  统计这K个邻居的类别频率
##### 步骤5  K个邻居里频率最高的类别，即为测试对象的类 
######    测试结果统计表
测试序号 | K值 | 错误数 | 错误率
-|-|-|-
1 | 1 | 347 | 0.0127
2 | 3 | 326 | 0.0105
3 | 5 | 371 | 0.0179
4 | 7 | 349 | 0.0222
5 | 9 | 353 | 0.0222
6 | 11 | 369 | 0.0200
7 | 13 | 370 | 0.0253
8 | 15 | 387 | 0.0264
##### K=3时错误率最低，只有0.01。一般情况下在KNN算法中k的取值过小或过大都不是很适合，过小的话容易发生过拟合；过大的话会使更多的训练实例对测试集产生影响，近似误差会增大。

