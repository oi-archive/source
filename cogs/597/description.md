# 题目描述


<p>
<b>【问题描述】</b><br/>
    有两行自然数， UP[1..N] ， DOWN[1..M] ，如果 UP[I]=DOWN[J]=K ，那么上行的第 I 个位置的数就可以跟下行的第 J 个位置的数连一条线，称为一条 K 匹配，但是 <strong>同一个位置 </strong>的数最多只能连一条线。另外，每个 K 匹配都 <strong>必须且至多 </strong>跟一个 L 匹配相交且 <strong>K </strong><strong>≠ </strong><strong>L </strong>！现在要求一个最大的匹配数。
</p>
<p>
【输入格式】 <br/>
    第一行有两个正整数 N 和 M 。第二行 N 个 UP 的自然数，第三行 M 个 DOWN 的自然数。其中 0&lt;N 、 M&lt;=200 ， UP 、 DOWN 的数都不超过 32767 。
</p>
<p>
【输出格式】 <br/>
   最大匹配数 。
</p>
<p>
【输入输出样例1】 <b><br/>
</b>输入:
</p>
<pre>crossa.in
12 11
1 2 3 3 2 4 1 5 1 3 5 10
3 1 2 3 2 4 12 1 5 5 3</pre>
<p>
输出:
</p>
<pre>crossa.out
8</pre>
<p>
【输入输出样例2】 <b><br/>
</b>输入:
</p>
<pre>crossa.in
4 4
1 1 3 3
1 1 3 3</pre>
<p>
输出:
</p>
<pre>crossa.out
0</pre>
