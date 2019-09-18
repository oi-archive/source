# 题目描述


<h3>
【题目描述】
</h3>
<p>
输入正整数N，求G的值。G如下定义：
</p>
<p>
<img src="/upload/image/20140111/20140111133801_21447.gif" alt=""/> 
</p>
<p>
这里GCD(i,j)代表i,j的最大公约数。
</p>
<p>
对于不理解求和符号的人，下面给出了G的代码表示：
</p>
<pre class="prettyprint lang-cpp">G=0;
for(i=1;i&lt;N;i++)
for(j=i+1;j&lt;=N;j++)
{
    G+=gcd(i,j);
}
/*gcd(i,j)的值是i,j的最大公约数*/</pre>
<h3>
【输入格式】
</h3>
<p>
输入包含至多100组数据。每组数据占一行，包含正整数N(2&lt;=N&lt;=1&lt;N&lt;4000000)。输入以N=0结束。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组数据，输出一行，即所对应的G值。答案保证在64位带符号整数范围内。
</p>
<h3>
【样例输入】
</h3>
<pre>10
100
200000
0</pre>
<h3>
【样例输出】
</h3>
<pre>67
13015
143295493160</pre>
<h3>
【提示】
</h3>
<p>
对于30%的数据，2&lt;=N&lt;=2000
</p>
<p>
对于100%的数据，2&lt;=N&lt;=4000000
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=473&amp;page=show_problem&amp;problem=2421" target="_blank">UVa 11426 GCD - Extreme (II)</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2.4
</p>
