# AMT-denoised
AMT denoising code based on self-supervised learning

每个jupyter notebook程序都在Tags的v1.0中

**prepare_data**用于**对单线每个点(01U)的每个通道(Ex,Ey,Hx,Hy)制作一个.npy文件**，用于转换Tsn格式为npy格式

**Simulation experiment**用于仿真加噪实验

**train_H**用于训练磁道

**method compare inversion**用于与其他方法的反演结果对比

**method compare timeseries**用于与其他方法的时序结果对比

**MT_train**用于训练MT数据

**mtpyplot**用于使用mtpy绘图包成图

**n2n-denoise**主程序，包括dataset，mask，metric，loss，train等主要程序

**n2n-plot**绘制时序数据

**n2n-test**前向预测主程序

**predict**预测主程序

**ckpts**用于存储训练权重文件夹

**data1**数据集制作示例

**ediexample**视电阻率-相位结果示例

**mask1**样本掩码示例

**result1**去噪前后时序对比

**SigMT**SigMT库，用于绘制反演结果（相干度、极化方向）
