![image-20210316110724494](images/image-20210316110724494.png)

![image-20210316110908159](images/image-20210316110908159.png)

![image-20210316112237052](images/image-20210316112237052.png)

![image-20210316112553249](images/image-20210316112553249.png)

![image-20210316120141919](images/image-20210316120141919.png)



| 超参数类型 | 默认值                                 |
| ---------- | -------------------------------------- |
| 初始化     | He初始化                               |
| 激活函数   | ELU                                    |
| 归一化     | 浅层网络：不需要；深度网络：批量归一化 |
| 正则化     | 提前停止（如果需要，可加l2)            |
| 优化器     | 动量优化(or RMSProp or Nadam)          |
| 学习率调度 | 1周期                                  |


| 超参数类型 | 默认值                        |
| ---------- | ----------------------------- |
| 初始化     | Lecun初始化                   |
| 激活函数   | SELU                          |
| 归一化     | 不需要                        |
| 正则化     | 如果需要：alpha dropout       |
| 优化器     | 动量优化(or RMSProp or Nadam) |
| 学习率调度 | 1周期                         |
