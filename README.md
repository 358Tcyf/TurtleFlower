# TurtleFlower
这套程序使用python turtle绘制繁花曲线

代码中绘图的原理已经封装成了flower函数，想画图的话指定后边的参数即可。
一共6个参数，前三个参数分别是大圆半径，小圆半径，画笔离小圆边缘的距离。
第四个参数是分辨率，这个数越小画图越精细但也越慢，另外精细程度有上限，推荐使用0.01，设置得大一些画的快，但是粗糙，不过也可能得到意想不到的效果。
第五个参数是颜色，turtle默认了一些颜色，‘red‘’yellow‘’green‘等，你也可以用自定义的RGB颜色，格式是’＃000000‘。想要画渐变色的话就要修改flower里的代码了。
最后一个参数是画笔粗细。

可以多次调用flower画多个繁花曲线，但现在的代码只能绘制同心的繁花曲线。
