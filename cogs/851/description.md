# 题目描述


<p>
	<span style="font-family:宋体;">【题目描述】</span> 
</p>
<p>
	<span style="font-family:宋体;">有一个长度为</span><span>n</span><span style="font-family:宋体;">的数列</span><span>c_i</span><span style="font-family:宋体;">，我们每次可以执行一个下面的操作之一</span><span>:</span> 
</p>
<p>
	<span>1.</span><span style="font-family:宋体;">选择一个区间</span><span>[l,r]</span><span style="font-family:宋体;">，区间内每个数加上</span><span>a</span> 
</p>
<p>
	<span>2.</span><span style="font-family:宋体;">选择一个区间</span><span>[l,r]</span><span style="font-family:宋体;">，区间内每个数减去</span><span>a</span> 
</p>
<p>
	<span>3.</span><span style="font-family:宋体;">选择一个区间</span><span>[l,r]</span><span style="font-family:宋体;">，区间内每个数加上</span><span>b</span> 
</p>
<p>
	<span>4.</span><span style="font-family:宋体;">选择一个区间</span><span>[l,r]</span><span style="font-family:宋体;">，区间内每个数减去</span><span>b</span> 
</p>
<p>
	<span style="font-family:宋体;">现在想用最少的操作次数使得数列的每个元素都变为</span><span>0</span><span style="font-family:宋体;">，请你计算出最少的操作次数</span> 
</p>
<p>
	<span style="font-family:宋体;">【输入格式】</span> 
</p>
<p>
	<span style="font-family:宋体;">第一行三个整数</span><span>n</span><span style="font-family:宋体;">，</span><span>a</span><span style="font-family:宋体;">，</span><span>b</span><span style="font-family:宋体;">，含义如题目所示</span> 
</p>
<p>
	<span style="font-family:宋体;">接下来一行</span><span>n</span><span style="font-family:宋体;">个整数，表示数列</span><span>c_i</span> 
</p>
<p>
	<span style="font-family:宋体;">【输出格式】</span> 
</p>
<p>
	<span style="font-family:宋体;">一行一个整数，表示最少的操作次数。如果没有可行方案，直接输出</span><span>-1</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输入】</span> 
</p>
<p>
	<span>5 2 3</span> 
</p>
<p>
	<span>1 2 1 1
-1</span> 
</p>
<p>
	<span style="font-family:宋体;">【样例输入】</span> 
</p>
<p>
	<span>5</span> 
</p>
<p>
	<span style="font-family:宋体;">【数据规模】</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>30%</span><span style="font-family:宋体;">的数据，</span><span>1 &lt;=
n,a,b &lt;= 200, -200 &lt;= c_i &lt;= 200</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>60%</span><span style="font-family:宋体;">的数据，</span><span>1 &lt;=
n,a,b &lt;= 2000, -2000 &lt;= c_i &lt;= 2000</span> 
</p>
<p>
	<span style="font-family:宋体;">对于</span><span>100%</span><span style="font-family:宋体;">的数据，</span><span>1 &lt;= n
&lt;= 100000, 1 &lt;= a, b &lt;= 10^9, -10^9 &lt;= c_i &lt;= 10^9</span> 
</p>
<p>
	<span style="font-family:宋体;">【时限】</span> 
</p>
<p>
	<span>2s</span> 
</p>
