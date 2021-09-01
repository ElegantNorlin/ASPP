# ASPP
A pytorch implementation of ASPP modul.

空洞空间卷积池化金字塔(atrous spatial pyramid pooling (ASPP))对所给定的输入以不同采样率的空洞卷积并行采样，相当于以多个比例捕捉图像的上下文。

每一个空洞卷积都会获得更大的感受野，对于大尺寸目标的检测效果比较友好。

ASPP可以获取不同尺度特征的空间信息，可以理解为多尺度的上下文信息。

