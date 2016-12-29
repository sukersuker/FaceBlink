# 活体检测FaceBlink

`support for iOS8+`

这个工程Demo是以人脸识别算法为基础，将一系列活体检测与人脸检测参数列出来给测试人员调试用，用于优化上朝啦app。

关于活体检测本质是判断的眼睛眨眼开合度。
当获取到连续帧图片中的人眼开合度后，就是获取到了多个开合度数值，如果连起来就可以认为是一条线，当眨眼的时候就认为这条线产生了波动。判断波动的方式就是采用了这一串开合度的值计算方差的原理。

![image](https://github.com/MQL9011/FaceBlink/blob/master/img/IMG.png)

主要调试参数如下：
* 连续检测多少帧照片
* 眨眼队列存放值个数
* 眨眼平均值偏差
* 眨眼队列开合度方差
* 人脸中心点坐标x
* 人脸中心点坐标y
* 俯仰角度
* 左右角度
* 旋转角度
* 人脸高度大于


```

```

                                                                                         

