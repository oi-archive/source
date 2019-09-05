# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
一天，S感觉无聊至极，于是他做了一件很无聊的事：
</p>
<p>
他在纸上画了N个点，并加上环，也就是说，在每个点上都有一条自环边，接着，他又随机地在不同的点之间加了几条边，并且保证在任两个点之间不超过一条边。这样他就得到了一个没有重边的无向图G，最后，他画出了图G的邻接矩阵，并且计算出了A^2。
</p>
<p>
现在只给你A^2，S想知道是否存在一种方案，使得每条边都恰好只经过一次，并且结束点同时也是出发点，你能回答他吗？
</p>
<p>
<br/>
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
输入文件第一行是一个整数T(T&lt;=20)，表示接下来测试数据的个数，每个测试数据格式如下:
</p>
<p>
第一行是一个正整数N(N&lt;=100)，表示图中顶点的个数，接下来有N行，每一行有N个空格隔开的整数，其中第i行第j个整数表示矩阵A^2中的第（i,j）个元素。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个测试数据，在一行输出字符串&#34;Yes&#34;或者&#34;No&#34;（不包括引号），做为上面相应的问题的回答。
</p>
<h3>
【样例输入】
</h3>
<pre>2
1
1
2
2 2
2 2
</pre>
<h3>
【样例输出】
</h3>
<pre>Yes
No
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
B=A^2
</p>
<p>
当且仅当B(i,j)=∑(A(i,k)*A(k,j)) 0&lt;=k&lt;n
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>