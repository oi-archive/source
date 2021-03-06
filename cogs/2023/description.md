# 题目描述


<h3>
【题目描述】
</h3>
<p>
小园丁Mr. S负责看管一片田野，田野可以看作一个二维平面。
</p>
<p>
田野上有 n 棵许愿树，编号$1,2,3,⋯,n$，每棵树可以看作平面上的一个点，其中第$i$棵树$(1≤i≤n)$位于坐标$(x_i,y_i)$。任意两棵树的坐标均不相同。
</p>
<p>
老司机Mr. P从原点$(0,0)$驾车出发，进行若干轮行动。每一轮，Mr. P首先选择任意一个满足以下条件的方向：
</p>
<p>
为左、右、上、左上 45°、右上 45°五个方向之一。
</p>
<p>
沿此方向前进可以到达一棵他尚未许愿过的树。
</p>
<p>
完成选择后，Mr. P沿该方向直线前进，必须到达该方向上距离最近的尚未许愿的树，在树下许愿并继续下一轮行动。如果没有满足条件的方向可供选择，则停止行动。他会采取最优策略，在尽可能多的树下许愿。若最优策略不唯一，可以选择任意一种。
</p>
<p>
不幸的是，小园丁Mr. S发现由于田野土质松软，老司机Mr. P的小汽车在每轮行进过程中，都会在田野上留下一条车辙印，一条车辙印可看作以两棵树（或原点和一棵树）为端点的一条线段。
</p>
<p>
在Mr. P之后，还有很多许愿者计划驾车来田野许愿，这些许愿者都会像Mr. P一样任选一种最优策略行动。Mr. S认为非左右方向（即上、左上 45° 、右上 45° 三个方向）的车辙印很不美观，为了维护田野的形象，他打算租用一些轧路机，在这群许愿者到来之前夯实所有“可能留下非左右方向车辙印”的地面。“可能留下非左右方向车辙印”的地面应当是田野上的若干条线段，其中每条线段都包含在某一种最优策略的行进路线中。每台轧路机都采取满足以下三个条件的工作模式：
</p>
<p>
从原点或任意一棵树出发。
</p>
<p>
只能向上、左上 45° 、右上 45° 三个方向之一移动，并且只能在树下改变方向或停止。
</p>
<p>
只能经过“可能留下非左右方向车辙印”的地面，但是同一块地面可以被多台轧路机经过。
</p>
<p>
现在Mr. P和Mr. S分别向你提出了一个问题：
</p>
<p>
请给Mr .P指出任意一条最优路线。
</p>
<p>
请告诉Mr. S最少需要租用多少台轧路机。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第1行包含1个正整数n，表示许愿树的数量。接下来n行，第i+1行包含2个整数$x_i,y_i$，中间用单个空格隔开，表示第i棵许愿树的坐标。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件包括 3 行。输出文件的第 1 行输出 1 个整数 m，表示 Mr. P 最多能在多少棵树下许愿。输出文件的第 2 行输出 m 个整数，相邻整数之间用单个空格隔开，表示 Mr. P 应该依次在哪些树下许愿。输出文件的第 3 行输出 1 个整数，表示 Mr. S 最少需要租用多少台轧路机。
</p>
<h3>
【样例输入】
</h3>
<p>
6
</p>
<p>
-1 1
</p>
<p>
1 1
</p>
<p>
-2 2
</p>
<p>
0 8
</p>
<p>
0 9
</p>
<p>
0 10
</p>
<h3>
【样例输出】
</h3>
<p>
3
</p>
<p>
2 1 3
</p>
<p>
3
</p>
<h3>
【提示】
</h3>
<p>
最优路线 2 条可许愿 3 次：
</p>
<p>
$(0,0)→(1,1)→(−1,1)→(−2,2)(0,0)→(1,1)→(−1,1)→(−2,2)$ 或 $(0,0)→(0,8)→(0,9)→(0,10)(0,0)→(0,8)→(0,9)→(0,10)$。 
</p>
<p>
至少 3 台轧路机，路线是 
</p>
<p>
$(0,0)→(1,1)(0,0)→(1,1)，(−1,1)→(−2,2)(−1,1)→(−2,2)$ 和 $(0,0)→(0,8)→(0,9)→(0,10)(0,0)→(0,8)→(0,9)→(0,10)$。
</p>
<h3>
【题目来源】
</h3>
<p>
NOI 2015
</p>
