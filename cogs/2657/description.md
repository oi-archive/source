# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<div>
Doris刚刚学习了$fibonacci$数列。用$f[i]$表示数列的第$i$项，那么
</div>
<p>
$$\begin{align}f[0]&amp;=0\\f[1]&amp;=1\\f[n]&amp;=f[n-1]+f[n-2],n&gt;=2\end{align}$$
</p>
<div>
Doris用老师的超级计算机生成了一个$n\times m$的表格，第$i$行第$j$列的格子中的数是$f[\mathrm{gcd}(i,j)]$，其中$\mathrm{gcd}(i,j)$表示$i$,$j$的最大公约数。Doris的表格中共有$n\times m$个数，她想知道这些数的乘积是多少。答案对$10^9+7$取模。
</div>
<div>
</div>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
有多组测试数据。第一个一个数$T$，表示数据组数。
</p>
<p>
接下来$T$行，每行两个数$n,m$
</p>
<p>
$T \leq 1000$,$1 \leq n$,$m \leq 10^6$
</p>
<h3>
【输出格式】
</h3>
<div class="content">
<div>
 输出$T$行，第$i$行的数是第$i$组数据的结果
</div>
<div>
</div>
</div>
<h3>
【样例输入】
</h3>
<pre>3
2 3
4 5
6 7
  </pre>
<h3>
【样例输出】
</h3>
<pre>1
6
960</pre>
