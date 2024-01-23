# A Second-Pricing Based Incentive-Compatible Mechanism for Matching and Pricing in Ride-Sharing
这是一个使用python实现的基于次价的共享出行匹配和定价激励兼容机制算法。

## 文件说明：

agent文件夹：定义平台、代理投标者、用户投标以及车辆的信息

algorithm文件夹：实现订单匹配与定价，以及路径规划算法

data文件夹：存放预处理后的车辆数据以及订单数据

env文件夹：定义交通路网环境

preprocess文件夹：订单数据的清洗与筛选以及路网节点的聚类

result文件夹：.pkl文件存放最终结果

runner文件夹：加载环境以及数值实验

## 实验复现：

运行runner文件夹中的main.py文件

`python main.py`

## 运行条件：

- python 3.6
- numpy 1.19.2
- pandas 1.1.5
- lapsolver 1.1.0











