## 房价预测

### 目标

根据房屋属性预测每个房子的最终价格

### 任务流程

* 分析数据指标
    * 不同指标对结果的影响
    * 连续值与离散值的情况 

* 观察数据正态性
    * 是否满足正态分布
    * 数据变换操作

* 数据预处理
    * 缺失值填充
    * 标签转换

* 集成方法建模对比
    * 单模型回归效果
    * 平均与堆叠模型效果对比


### 数据集

* 有关数据集的各个列的特征描述在`data`文件夹下面的`data_description.txt`中。(Note:**特征比较多！**)
* 数据集在`data`文件夹里面, 包含`train.csv`和`test.csv`两个文件


### 配置环境

* Python 3.6.5
* numpy 1.15.4
* scipy 1.1.0
* pandas 0.23.4
* matplotlib 3.0.2
* seaborn 0.9.0
* scikit-learn 0.20.1