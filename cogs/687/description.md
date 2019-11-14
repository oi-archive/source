# 题目描述


<h3>
【题目描述】
</h3>
<p>
给定$n$个变量，$m$个不等式。
</p>
<p>
不等式之间具有传递性，即若$A&gt;B$,且$B&gt;C$，则$A&gt;C$。
</p>
<p>
判断这$m$个不等式是否有矛盾。
</p>
<p>
若无矛盾，则判断这$m$个不等式是否能确定每一对边两者间的关系，
</p>
<p>
   若能，则求出$t$的最小值，满足仅用前$t$个不等式就能确定每一对变量之间的大小关系。
</p>
<h3>
【输入格式】
</h3>
<p>
有多组测试数据。
</p>
<p>
对于每一组测试数据：
</p>
<p>
第一行两个整数，表示$n$,$m$。
</p>
<p>
  $n$表示前$n$个大写字母
</p>
<p>
接下来$m$行每行一共三个字符，第一个大写字母，字符“&lt;”和第二个大写字母，没有字母超出字母表的前n个字母的范围。
</p>
<p>
以0 0结尾作为结束标志
</p>
<h3>
【输出格式】
</h3>
<p>
对于每一组测试数据，输出由一行组成，一共有三种情况：
</p>
<p>
Sorted sequence determined after xxx relations: yyy...y.
</p>
<p>
Sorted sequence cannot be determined.
</p>
<p>
Inconsistency found after xxx relations. 
</p>
<p>
表示：<br/>
其中xxx是在确定排序序列或找到不一致时处理的关系数，以靠前者为准，yyy 是已排序的升序序列。
</p>
<h3>
【样例输入】
</h3>
<pre>4 6
A&lt;B
A&lt;C
B&lt;C
C&lt;D
B&lt;D
A&lt;B
3 2
A&lt;B
B&lt;A
26 1
A&lt;Z
0 0
</pre>
<h3>
【样例输出】
</h3>
<pre>Sorted sequence determined after 4 relations: ABCD.
Inconsistency found after 2 relations.
Sorted sequence cannot be determined.
</pre>
<h3>
【提示】
</h3>
<p>
$2&lt;=n&lt;=26$
</p>
<h3>
【来源】
</h3>
<p>
East Central North America 2001   POJ 1094
</p>
