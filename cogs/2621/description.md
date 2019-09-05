# 题目描述


<h3>
【题目描述】
</h3>
<p>
今天某只名字很长的蒟蒻从poj切掉了一道计算几何的题<a href="http://poj.org/problem?id=2194" target="_blank">poj 2194 Stacking Cylinders</a> ，这是一道可以0MS解决的好题，题意是这样的:
</p>
<p>
    有n(n&lt;=10)个半径为1的圆堆叠在一起,它们被成了好多层.其中最下面那层有n个圆,从下往上每层圆依次减少1个.且上层的圆一定是与下层两个相邻的圆相切的.给定你最下层n个圆的圆心坐标,要你输出最上一层的圆心坐标.
</p>
<p>
<img src="/upload/image/20170228/20170228173643_83172.jpg" alt=""/> 
</p>
<p>
    做完这道题，这只名字很长的蒟蒻开始颓废，它产生了很多的脑冻，而且受到这道题的影响，它的脑冻也变成了n(n&lt;=1000000)个半径为1的圆，它现在也想得到最顶上脑冻的圆心坐标。
</p>
<p>
    这只名字很长的蒟蒻发现他的程序很快的跑完了，于是它想对拍一下检查自己做的对不对，但它从网上找的飙程有很多一直跑不出来，（当然不是数组大小问题），而有的彪程却能像它一样快速出解，现在它迷糊了，它的程序到底对不对呢？请你写一个膘程帮忙检验一下吧！
</p>
<h3>
【输入格式】
</h3>
<p>
第一行1个整数n(n&lt;=1000000)
</p>
<p>
第二行n个实数为最底层n个脑冻的圆心横坐标（按从左到右的顺序给出），同时为了保证这道题不变成一道物理题，将原题的限制条件放在这里：
</p>
<p>
The distance between adjacent centers will be at least 2.0 (so the cylinders do not overlap) but no more than 3.4 (cylinders at level k will never touch cylinders at level k – 2).
</p>
<h3>
【输出格式】
</h3>
<p>
两个实数为最顶层脑冻圆心的坐标（保留4位小数）。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
4
</p>

<p>
1.0 4.4 7.8 11.2<span style="font-family:monospace;"></span> 
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>6.1000 4.1607</pre>
<h3>
【提示】
</h3>
<p>
对于10%的数据,n&lt;=10
</p>
<p>
对于30%的数据,n&lt;=1000
</p>
<p>
对于100%的数据,n&lt;=1000000
</p>
<h3>
【来源】
</h3>
<p>
一只名字很长的蒟蒻
</p>