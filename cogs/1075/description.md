# 题目描述


<h2>
 [问题描述] 
</h2>
<p>
平面上有n个点（n&lt;=100），每个点的坐标均在-10000~10000之间。其中的一些点之间有连线。若有连线，则表示可从一个点到达另一个点，即两点间有通路，通路的距离为两点间的直线距离。现在的任务是找出从一点到另一点之间的最短路径。
</p>
<h2>
[输入格式] 
</h2>
<p style="text-indent:21.0000pt;">
输入文件为short.in，共n+m+3行，其中:
</p>
<p style="text-indent:21.0000pt;">
第一行为整数n。
</p>
<p style="text-indent:21.0000pt;">
第2行到第n+1行（共n行），每行两个整数x和y，描述了一个点的坐标。
</p>
<p>
    第n+2行为一个整数m，表示图中连线的个数。
</p>
<p>
    此后的m行，每行描述一条连线，由两个整数i和j组成，表示第i个点和第j个点之间有连线。
</p>
<p>
    最后一行：两个整数s和t，分别表示源点和目标点。
</p>
<h2>
[输出格式] 
</h2>
<p style="text-indent:21.0000pt;">
输出文件为short.out，仅一行，一个实数（保留两位小数），表示从s到t的最短路径长度。
</p>
<p style="text-indent:21.0000pt;">
<br/>
</p>
<h2>
[样例输入]
</h2>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
5
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
0 0
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
2 0
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
2 2
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
0 2
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
3 1
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
5
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
1 2
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
1 3
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
1 4
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
2 5
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
3 5
</p>
<p style="margin-left:47.1450pt;text-indent:0.0500pt;">
1 5
</p>
<h2>
[<span>样例输出</span><span>]</span> 
</h2>
<p style="text-indent:47.2500pt;">
3.41
</p>
