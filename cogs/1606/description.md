# 题目描述


<h3>
【题目描述】
</h3>
<p>
考虑一个数列a[i]，i=0,1,2,...,以如下规则定义：
</p>
<p>
a[0]=0
</p>
<p>
a[1]=1
</p>
<p>
a[2i]=a[i]
</p>
<p>
a[2i+1]=a[i]+a[i+1]
</p>
<p>
其中i=1,2,3,...
</p>
<p>
写一个程序，对于给定的N(0 &lt; N &lt; 10^18)，找到a[0],a[1],...,a[N]中最大的数。
</p>
<h3>
【输入格式】
</h3>
<div class="ptx" lang="zh-CN">
输入文件包含不超过10000行，每行一个整数N。输入文件的最后一行是一个0.
</div>
<h3>
【输出格式】
</h3>
<div class="ptx" lang="zh-CN">
对每一个N（除了最后的0），输出一行即相应的最大值。
</div>
<h3>
【样例输入】
</h3>
<pre class="sio">5
10
0</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">3
4</pre>
<h3>
【提示】
</h3>
<p>
答案或中间变量的值可能超过64位有符号整数的范围，请使用64位无符号整数或实数类型。
</p>
<h3>
【来源】
</h3>
<div class="ptx" lang="zh-CN">
<a href="http://acm.timus.ru/problem.aspx?num=1396" target="_blank">Ural 1396 Maximum. Version 2 </a> 
</div>
<div class="ptx" lang="zh-CN">
<b>Problem Author:<span class="Apple-converted-space"> </span></b>Prepared by Vladimir Yakovlev<span class="Apple-converted-space"> </span> 
</div>
