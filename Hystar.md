# Hystar

液质联用数据处理，Hystar PP，DataAnalysis

## Hystar PP

1. 启动软件：Start\Program\Bruker daltonics\hystar\hystar PP 

> 打开数据文件：
 
>>在数据文件夹下打开数据文件；*.unt文件为1D数据，*.u2文件为2D数据。

>>> **只有在Hystar液相方法编辑中设置保存2D数据才会产生\*.u2文件**，2D数据窗口包括选定时间下的全紫外扫描数据、三维数据和选定波长下的紫外色谱图。

>>> *三维数据显示窗口中，不同颜色代表信号强弱，纵轴为波长，横轴为保留时间。

>>> 可打开多个*.unt文件，支持多1D数据窗口显示。可选择同时显示多个波长下的紫外色谱图；可显示色谱参数，如泵压、流速和梯度线等；只可显示Hystar液相方法编辑页面下Detector设置中添加的信号；也可显示MS信号。

>> 色谱图处理和结果：菜单栏Process下，依次选择Peak detection、Peak integration和Peak Results。

>> 在色谱峰检测前，可自定义峰检测参数，<LC>设置紫外色谱图。（Peak parameter：最少数据采集点；Slope：峰形参数，推荐设定200）。<MS>设置质谱离子流图（Sensitivity：基线噪音值；Smoothing：峰形平滑）若在色谱峰检测之后，可重新定义参数后重新处理数据。

* 结果列表中包括所有色谱相关信息，如峰高、峰宽、信噪比、峰面积和相对峰面积等。

>> 打印报告

2. DataAnalysis

* 浏览和处理液质联用的紫外色谱图；浏览和处理质谱离子刘色谱图；单独液相色谱数据不能处理。

>> 色谱图浏览。可添加和编辑色谱图；可覆盖或并列等形式同时显示多种色谱图，便于比较；可自定义色谱图的显示颜色。

>>> 对色谱峰的检测和积分，已得到色谱峰对应的化合物的质谱图；还可以自动扣除背景。

# 液质联用操作步骤

## LC

* 使用前检查所用色谱柱（6-1或2-1）

>> 操作步骤：打开变色龙软件→home→take control（可以调V=0）→F8 domum oven→valve right（6-1 2-1）→EX（执行）

* **赶气泡、洗柱子、平衡柱子**

>> LC管道有气泡，拧开圆阀进行purge