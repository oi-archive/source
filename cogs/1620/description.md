# 题目描述


<h3>
【题目描述】
</h3>
<p>
考虑1到n的整数。我们把一个整数的各位数字和叫做其权值。记x的权值为w(x)。
</p>
<p>
现在我们把这些数字按照被称作“高级字典序”的顺序排序。考虑两个整数a和b。如果w(a)&lt;w(b)那么在高级字典序中，a在b之前。如果w(a)=w(b)，那么在高级字典序中a位于b之前的充要条件是在十进制下a的字典序比b的字典序小。
</p>
<p>
让我们考虑一些例子。
</p>
<p>
注：以下的“&lt;”均指在高级字典序中，前者位于后者之前。
</p>
<p>
120 &lt; 4，因为w(120) = 1 + 2 + 0 = 3 &lt; 4 = w(4).
</p>
<p>
555 &lt; 78，因为w(555) = 15 = w(78)，并且“555”的字典序比“78”小。
</p>
<p>
20 &lt; 200， 因为w(20) = 2 = w(200)并且“20”的字典序比“200”小。
</p>
<p>
给出n和一个整数k，找到k在1~n的高级字典序中排第几个，以及1~n的高级字典序中第k小的数。
</p>
<h3>
【输入格式】
</h3>
<p>
一行两个整数n,k（1&lt;=k&lt;=n&lt;=10^18）。
</p>
<h3>
【输出格式】
</h3>
<p>
两个整数：k在1~n高级字典序中的位置，以及1~n高级字典序中的第k个数。
</p>
<h3>
【样例输入】
</h3>
<pre>20 10</pre>
<h3>
【样例输出】
</h3>
<pre>2 14</pre>
<h3>
【提示】
</h3>
<p>
这里的输入格式和ZOJ原题略有不同。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://acm.zju.edu.cn/onlinejudge/showProblem.do?problemCode=2599" target="_blank">ZOJ 2599 Graduated Lexicographical Ordering</a> 
</p>
<p>
Author: Andrew Stankevich
</p>
<p>
Source: Andrew Stankevich&#39;s Contest #6
</p>
