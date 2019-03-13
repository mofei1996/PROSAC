# PROSAC 说明

## 功能
* 使用 PROSAC 实现对单映矩阵(Homography)的快速计算

## 注意
* 代码使用 OpenCV3 实现
* 代码中没有实现对 $\beta$ 的动态估计
* 代码中的 $\beta$ 需要选取较大的数值
* 代码中对 $k_{n^*}(\eta_o)$ 和 $n^*$ 的计算可能不能用于其他任务中
* 代码中排序的程序可以根据自己的需求进行修改