# 题目描述


<h3>
【问题描述】
</h3>
<p>
给一个N个点M条边的连通无向图，满足每条边最多属于一个简单环，有Q组询问，每次询问两点之间的最短路径。
</p>
<h3>
【输入格式】
</h3>
<p>
输入的第一行包含三个整数，分别表示N和M和Q<br/>
下接M行，每行三个整数v，u，w表示一条无向边v-u，长度为w(&lt;=1000)<br/>
最后Q行，每行两个整数v，u表示一组询问
</p>
<h3>
【输出格式】
</h3>
<p>
输出Q行，每行一个整数表示询问的答案
</p>
<h3>
【样例输入】
</h3>
<pre>9 10 2
1 2 1
1 4 1
3 4 1
2 3 1
3 7 1
7 8 2
7 9 2
1 5 3
1 6 4
5 6 1
1 9
5 7
</pre>
<h3>
【样例输出】
</h3>
<pre>5
6
</pre>
<h3>
【数据说明】
</h3>
<p>
对于5%的数据，N&lt;=100<br/>
对于20%的数据，N&lt;=1000<br/>
对于100%的数据，N&lt;=10000，Q&lt;=10000<br/>
对于100%的数据，时间限制为0.1s。
</p>
<h3>
【试题来源】
</h3>
<p>
2011中国国家集训队命题答辩
</p>