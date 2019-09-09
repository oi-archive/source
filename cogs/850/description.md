# 题目描述


<p>
	<span style="font-family:宋体;">【题目描述】</span> 
</p>
<p>
	<span style="font-family:宋体;">现在有一张</span><span>n</span><span style="font-family:宋体;">列的棋盘，每一列的高度为</span><span>h_i</span><span style="font-family:宋体;">，每一列的底在同一水平线上。</span> 
</p>
<p>
	<span style="font-family:宋体;">然后你需要在这个棋盘上放</span><span>k</span><span style="font-family:宋体;">个象棋里的车，使得他们互不攻击，问一共有多少种不同的摆放方法。注意两个车可以互相攻击当且仅当他们处在同一行或者同一列，而且中间的棋盘没有空缺。</span> 
</p>
<p>
	<span><img src="/images/upload/image/20120707/20120707073643_54238.jpg" alt=""/></span> 
</p>
<p>
	<span style="font-family:宋体;">上图是一张合法的棋盘，每列高度分别为</span><span>2</span><span style="font-family:宋体;">，</span><span>3</span><span style="font-family:宋体;">，</span><span>1</span><span style="font-family:宋体;">，</span><span>2</span><span style="font-family:宋体;">，</span><span>4</span><span style="font-family:宋体;">，而且两个</span><span>b</span><span style="font-family:宋体;">可以互相攻击，但是</span><span>a</span><span style="font-family:宋体;">不会互相攻击。</span> 
</p>
<p>
	<span style="font-family:宋体;">【输入格式】</span> 
</p>
<p>
	<span style="font-family:宋体;">第一行两个整数，</span><span>n</span><span style="font-family:宋体;">和</span><span>k</span><span style="font-family:宋体;">，分别表示棋盘列数和需要放的车的个数</span> 
</p>
<p>
	<span style="font-family:宋体;">接下来一行</span><span>n</span><span style="font-family:宋体;">个正整数</span><span>h_i</span><span style="font-family:宋体;">，表示每一列的高度</span> 
</p>
<p>
	<span style="font-family:宋体;">【输出格式】</span> 
</p>
<p>
	<span style="font-family:宋体;">一行一个整数，表示方案数。结果对</span><span>1000000007</span><span style="font-family:宋体;">取模</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输入</span><span>1</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>3 3 </span> 
</p>
<p>
	<span>2 1 3</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输出</span><span>1</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>2</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输入</span><span>2</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>5 2 </span> 
</p>
<p>
	<span>2 3 1 2
4</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输出</span><span>2</span><span style="font-family:宋体;">】</span> 
</p>
<p>
	<span>43</span> 
</p>
<p>
	<span style="font-family:宋体;">【数据范围】</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>40%</span><span style="font-family:宋体;">的数据，</span><span>0 &lt;=
n,k,h_i &lt;= 15</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>70%</span><span style="font-family:宋体;">的数据，</span><span>0 &lt;=
n,k,h_i &lt;= 100</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>100%</span><span style="font-family:宋体;">的数据，</span><span>0 &lt;= n,
k &lt;= 500, 0 &lt;= h_i &lt;= 1000000</span> 
</p>
<p>
	<span style="font-family:宋体;">【时限】</span> 
</p>
<p>
	<span>2s</span> 
</p>
