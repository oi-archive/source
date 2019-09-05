# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
给定一棵树，每条边有边权，树上所有节点均为白色
</p>
<p>
本蒟蒻想要施展大魔法，使得这棵树变成一棵黑色的树
</p>
<p>
然而本蒟蒻实在是太弱了，没有足够的能量来施展魔法
</p>
<p>
已知在这棵树上任意一条路径u-&gt;v(u不等于v),如果u-&gt;v路径上的所有边的边权的乘积是一个完全平方数，那么这条路径就会给你提供一点能量
</p>
<p>
现在本蒟蒻想知道，这棵树能给自己提供多少能量
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行n 表示节点总数
</p>
<p>
以下n-1行
</p>
<p>
每行u，v描述一条边的两个端点，w描述边权
</p>
<p>
n&lt;=200000，w&lt;=10^8
</p>
<p>
注意：对于两条路径，若u不同或者v不同，则这两条路径不同
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出一个数表示答案
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5
</p>

<p>
2 1 2
</p>

<p>
3 2 4
</p>

<p>
4 2 4
</p>

<p>
5 1 2
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>12</pre>