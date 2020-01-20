# canvas 气泡动画

canvas实现一个气泡的动画，点击画布的时候增加气泡。当气泡碰撞到画布边缘的时候会反弹回来，能同时改变颜色



思路：

画布的宽度为w,高度为y,球的半径为为r

每个新生成的气泡有2个随机值，一个表示x轴方向的移动比例movex，一个表示y轴方向的移动比例movey。

当气泡移动到左上角、左下角、右下角、右上角的时候movex,movey反向

当气泡移动到左边缘和右边缘的时候，movex反向

当气泡移动到上边缘和下边缘的时候，movey反向



![](https://img-blog.csdn.net/20170830213706371?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvY2NfZnlz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)
