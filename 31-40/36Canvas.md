### 问答题
1. 什么是 Canvas？Canvas 能干那些事？
    * html5中用来在网页上绘制图像。画布是一个矩形区域，可以控制每一个像素。
    * 拥有多种绘制路径、矩形、圆形、字符以及添加图像的方法

1. 画笔颜色，填充颜色各如何设置？
    * ctx.strokeStyle=;
    * ctx.fillStyle=;

1. Canvas 中如何画圆？如何填充圆？
    * ctx.arc(x,y,r,begin,end,true)
    * 通过画布。beginPath();closePath();ctx.fill();

1. Canvas 如何改变坐标系的位置和单位长度？
    * translate
    * scale(x, y)为坐标轴缩放因子，可以修改和原长度的比。默认为1,1

### 代码题
* [Link](https://github.com/a735315482/mfs-homework/blob/master/31-40/36.html)