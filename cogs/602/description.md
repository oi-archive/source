# 题目描述


<h3>
<span style="font-family:sans-serif;font-size:20px;font-weight:bold;background-color:aliceblue;">【题</span><span style="font-family:sans-serif;font-size:20px;font-weight:bold;background-color:aliceblue;">目描述】</span> 
</h3>
<p>
发展采矿业当然首先得有矿井，小  FF  花了上次探险获得的千分之一的财富请人在岛上挖了 n 口矿井，  但他似乎忘记考虑的矿井供电问题…… <br/>
为了保证电力的供应，  小 FF 想到了两种办法： <br/>
1、  在这一口矿井上建立一个发电站，  费用为  v（发电站的输出功率可以供给任意多个矿井）。 <br/>
2、  将这口矿井与另外的已经有电力供应的矿井之间建立电网，费用为 p。 <br/>
小 FF 希望身为”NewBe_One&#34;  计划首席工程师的你帮他想出一个保证所有矿井电力供应的最小花费。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数 n，表示矿井总数。 <br/>
第 2～n+1 行，每行一个整数，第 i 个数 v[i]表示在第 i 口矿井上建立发电站的费用。 <br/>
接下来为一个 n*n 的矩阵 P，其中 p[ i , j ]表示在第 i 口矿井和第 j 口矿井之间建立 <br/>
电网的费用（数据保证有 p[ i, j ] = p[ j, i ],  且  p[ i, i ]=0）。
</p>
<h3>
<span style="font-family:sans-serif;font-size:20px;font-weight:bold;background-color:aliceblue;">【输出格式】</span> 
</h3>
<p>
仅一个整数，表示让所有矿井获得充足电能的最小花费。 
</p>
<h3>
【输入样例】
</h3>
<pre>4
5
4
4
3
0 2 2 2
2 0 3 3
2 3 0 4
2 3 4 0
</pre>
<h3>
【输出样例】
</h3>
<pre>9
</pre>
<h3>
【提示】
</h3>
<p>
小 FF 可以选择在4号矿井建立发电站然后把所有矿井都与其建立电网，总花费是 3+2+2+2 = 9。
</p>
<h3>
【数据范围】
</h3>
<p>
对于30%的数据：1&lt;=n&lt;=50;
</p>
<p>
对于100%的数据：1&lt;=n&lt;=300;  0&lt;=v[i], p[i,j] &lt;=10^5.
</p>
<h3>
【来源】
</h3>
<p>
与 <a href="../problem/problem.php?pid=185" target="_blank">[USACO Oct08] 挖水井</a> 重题。
</p>
