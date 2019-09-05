# 题目描述


<h3>
【问题描述】
</h3>
<p>
国际象棋是世界上最古老的博弈游戏之一，和中国的围棋、象棋以及日本的将棋同享盛名。据说国际象棋起源于易经的思想，棋盘是一个8*8大小的黑白相间的方阵，对应八八六十四卦，黑白对应阴阳。
</p>
<p>
而我们的主人公小Q，正是国际象棋的狂热爱好者。作为一个顶尖高手，他已不满足于普通的棋盘与规则，于是他跟他的好朋友小W决定将棋盘扩大以适应他们的新规则。
</p>
<p>
小Q找到了一张由N*M个正方形的格子组成的矩形纸片，每个格子被涂有黑白两种颜色之一。小Q想在这种纸中裁减一部分作为新棋盘，当然，他希望这个棋盘尽可能的大。
</p>
<p>
不过小Q还没有决定是找一个正方形的棋盘还是一个矩形的棋盘（当然，不管哪种，棋盘必须都黑白相间，即相邻的格子不同色），所以他希望可以找到最大的正方形棋盘面积和最大的矩形棋盘面积，从而决定哪个更好一些。
</p>
<p>
于是小Q找到了即将参加全国信息学竞赛的你，你能帮助他么？
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件makechess.in的第一行包含两个整数N和M，分别表示矩形纸片的长和宽。
</p>
<p>
接下来的N行包含一个N * M的01矩阵，表示这张矩形纸片的颜色（0表示白色，1表示黑色）。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件makechess.out应包含两行，每行包含一个整数。
</p>
<p>
第一行为可以找到的最大正方形棋盘的面积，第二行为可以找到的最大矩形棋盘的面积（注意正方形和矩形是可以相交或者包含的）。
</p>
<h3>
【样例输入】
</h3>
<pre>3 3
1 0 1
0 1 0
1 0 0
</pre>
<h3>
【样例输出】
</h3>
<pre>4
6
</pre>
<h3>
【数据规模】
</h3>
<p>
对于20%的数据，N, M ≤ 80
</p>
<p>
对于40%的数据，N, M ≤ 400
</p>
<p>
对于100%的数据，N, M ≤ 2000
</p>