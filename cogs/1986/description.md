# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
$N$ 头奶牛被紧急动员起来了，它们排成了一条长列。从左向右看，排在第$i$个位置的奶牛身高为$H_i$<span style="line-height:1.5;">。约翰一声令下，所有奶牛向右看齐。假设每头奶牛只能看到比自己高的牛。请问它们各自看到的</span><span style="line-height:1.5;">最近的一头奶牛分别是谁呢？</span><span style="line-height:1.5;"></span> 
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
第一行：单个整数$N，1 ≤ N ≤ 10^6$
</p>
<p>
第二行到$N + 1$ 行：第$i + 1$ 行有一个整数$H_i，1 ≤ H_i ≤ 10^6$
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
第一行到第$N$ 行：第$i$ 行有一个整数$C_i$，表示第$i$ 头奶牛向右看到的最近的一头奶牛编号，如<span style="line-height:1.5;">果看不到任何奶牛，$C_i=0$</span><span style="line-height:1.5;"></span> 
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
6
3
2
6
1
1
2
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
3
3
0
6
6
0
</p>
</pre>
<h3>
【来源】
</h3>
<p>
USACO Mar09
</p>
