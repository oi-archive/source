# 题目描述


<h2>
问题描述
</h2>
<p>
给定一个有n个队伍的人组成的序列，第i个队伍i有s[i]个人组成，一个l到r的子序列是合法的，当且仅当<strong>$((\forall i)(\forall j) \land (i \ne j) \land (l \le i,j \le r)) \to (gcd(s[i], s[j]) = 1)$</strong>，即对于该序列中任两个不相同的队伍，他们人数的最大公约数为1，并且要求该子序列的总人数大于等于k。且由于每个队伍能够审批携带的仪器是有限的，所以需要这个队伍(r - l + 1)尽可能长，请求出这个队伍的最长长度，若不存在，请输出0。
</p>
<h2>
输入格式
</h2>
<p>
第一行两个整数n,k分别表示队伍数量和人数下限<br/>
接下来一行n个整数，表示每个队伍的人数
</p>
<h2>
输出格式
</h2>
<p>
一行一个整数，表示队伍的最长长度，如果不存在一个这样的队伍，则输出0
</p>
<h2>
输入样例
</h2>
<pre>5 14
4 5 12 3 2 
</pre>
<h2>
输出样例
</h2>
<pre>2 
</pre>
<h2>
数据范围
</h2>
<p>
<br/>
</p>
<p>
对于10%的数据$n \le 10$
</p>
<p>
对于另外20%的数据$n \le 10^2$
</p>
<p>
对于另外20%的数据$n \le 2 * 10^3$
</p>
<p>
对于全部的数据$1 \le n \le 10^5, 1 \le s[i] \le 10^6, k \le signed\ int$
</p>
<p>
<br/>
</p>