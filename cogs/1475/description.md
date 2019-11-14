# 题目描述


<h3>
【题目描述】
</h3>
<p>
若一个正整数的数字和被3整除，那么这个数也被3整除（反之亦然）。例如，3072被3整除，并且其数字和12也被3整除。这一性质对于模9也成立。
</p>
<p>
在这个问题中，我们将研究模其他正整数下的这个性质。
</p>
<h3>
【输入格式】
</h3>
<p>
第1行：一个正整数T(T&lt;100)，表示测试数据组数。<br/>
接下来的T行，每行包含3个正整数A,B,K。其中1&lt;=A&lt;=B&lt;2^31且0&lt;K&lt;10000.
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组测试数据，输出[A,B]内满足它和它的各位数字和同时被K整除的正整数个数。
</p>
<h3>
【样例输入】
</h3>
<pre>3
1 20 1
1 20 2
1 1000 4</pre>
<h3>
【样例输出】
</h3>
<pre>20
5
64</pre>
<h3>
【提示】
</h3>
<p>
对于20%的数据，1&lt;=A,B&lt;=20<br/>
对于100%的数据，1&lt;=A,B&lt;=2^31且0&lt;K&lt;10000,T&lt;100
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=469&amp;page=show_problem&amp;problem=2346" target="_blank">UVa 11361 Investigating Div-Sum Property</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2.2
</p>
