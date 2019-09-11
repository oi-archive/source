# 题目描述


<p class="MsoNormal">
<span style="color:#0000ff;"><span style="font-family:宋体;">题一</span><span lang="EN-US">  </span>求图形面积</span>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;"><b>【问题描述</b>】</span>
</p>
<p class="MsoNormal">
    具有不同颜色的 N 个小的矩形的纸被叠放在一张白纸上， 纸的尺寸是宽(左右)为A， 长(上下)为B，摆放矩形时使矩形的边与纸的边平行，并且每个矩形必须整个放在纸的边界之内。因此，不同颜色的各种不同图形可在纸上出现，同一颜色的两个区域中如果至少有一个公共点，则认为它们是同一图形的一部分，否则认为是不同的图形。 <br/>
    题目要求计算每一图形的面积。 A ， B 是正的偶数，且均不大于30 。坐标系统的定义为：坐标原点在纸的中心，两个轴分别平行于纸的两边。
</p>
<p class="MsoNormal">
【输入格式】
</p>
<p class="MsoNormal">
输入数据在文件中，其组成如下： <br/>
首行是 A,B,N , 中间用空格隔开,分别为宽和长及矩形的个数;<br/>
接下来有 N 行，每行有 空格隔开的 5 个数据，分别表示矩形左下角的横坐标、纵坐标、矩形右上角的横坐标、纵坐标、矩形的颜色（用 1-64 分别来表示一共的 64 种颜色，其中 1 表示白色）。
</p>
<p class="MsoNormal">
<span lang="EN-US"><o:p></o:p></span>【输出格式】
</p>
<p class="MsoNormal">
<span lang="EN-US">    要求每行输出一个彩色图形的颜色和对应图形的面积，按颜色代码的升序安排记录的输出顺序。(若有<span lang="EN-US">颜色</span>相同的不同图形,先输出靠左靠上的图形) </span>
</p>
<p class="MsoNormal">
【输入输出样例】
</p>
<p class="MsoNormal">
输入文件名：<span class="SpellE"> area.in</span>
</p>
<p class="MsoNormal">
20 12 5 <br/>
-7 -5 -3 -1 4 <br/>
-5 -3 5 3 2 <br/>
-4 -2 -2 2 4 <br/>
2 -2 3 -1 12 <br/>
3 1 7 5 1
</p>
<p class="MsoNormal">
输出文件名：<span class="SpellE"><span lang="EN-US">area.out</span></span>
</p>
<p class="MsoNormal">
<span lang="EN-US">1 172 <br/>
2 47 <br/>
4 12 <br/>
4 8 <br/>
12 1 </span>
</p>
