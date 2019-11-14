# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
FJ的牛已经决定去度假，并奇迹般地找到一个航空公司愿意出售他们的票。然而，当他们到达机场开始登机，面临的是一个有趣的问题 。
</p>
<p>
飞机有N个座位，我们叫位置x = 1到x = N，在一个数轴上。所有的奶牛 (1 &lt;= N &lt;= 200,000)正在排队在等待进入他们的座位。刚开始，奶牛N是在位置x = 0，奶牛N-1是在位置x = -1，等等。牛i被分配到牛座s_i，这里s_1，……，s_n是排列1，……，N.
</p>
<p>
在每一个时间步，每头奶牛需要走一步找到正确的座位如果她能。当奶牛i一到她的座位s_i，她将停下来，把她的行李放在上面的行李架上，用时t_i秒，然后坐下来。对于那些t_i秒时间，在她后面（如果有）的牛会被阻止向前。如果有一队牛在她身后，都将被阻止向前。
</p>
<p>
所有的牛坐好需要多久？
</p>
<p>
所有奶牛的t_i将少于1000000000。
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
第1行为N；
</p>
<p>
接下来有N行（2--N+1），两个整数s_i和t_i；
</p>
<p>
<br/>
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
输出只有一行，即需要的时间。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>3
2 5
3 10
1 5</pre>
<h3>
【样例输出】
</h3>
<pre>19</pre>
<h3>
【提示】
</h3>
<p>
<br/>
输入输出解释：<br/>
最初，牛是位于这样：<br/>
牛 -&gt; 123
 123&lt;- 座椅
</p><table border="1" width="200">
<tbody>
<tr>
<td>
 
</td>
<td>
-2
</td>
<td>
-1
</td>
<td>
0
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
<tr>
<td>
牛
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
</tr>
<tr>
<td>
座椅
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
</tbody>
</table>
<p></p>
<pre>牛1试图去坐2，2只想坐3，和牛3要座1。

一步后，他们都会向前走1步，牛3将达到她的座位1.
</pre>
<table border="1" width="200">
<tbody>
<tr>
<td>
 
</td>
<td>
-2
</td>
<td>
-1
</td>
<td>
0
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
<tr>
<td>
牛
</td>
<td>
 
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
<td>
 
</td>
<td>
 
</td>
</tr>
<tr>
<td>
座椅
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
</tbody>
</table>
<pre>牛3用时5秒放行李，然后坐到座位上.</pre>
<table border="1" width="200">
<tbody>
<tr>
<td>
 
</td>
<td>
-2
</td>
<td>
-1
</td>
<td>
0
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
<tr>
<td>
牛
</td>
<td>
 
</td>
<td>
1
</td>
<td>
2
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
</tr>
<tr>
<td>
座椅
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
</tbody>
</table>
<p>
3秒后奶牛1和奶牛2达到自己想要的座位：
</p>
<dl>
<dt>
 
</dt>
<dd>
 
</dd>
<dt>
 
</dt>
<table border="1" width="200">
<tbody>
<tr>
<td>
 
</td>
<td>
-2
</td>
<td>
-1
</td>
<td>
0
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
<tr>
<td>
牛
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
1
</td>
<td>
2
</td>
</tr>
<tr>
<td>
座椅
</td>
<td>
 
</td>
<td>
 
</td>
<td>
 
</td>
<td>
1
</td>
<td>
2
</td>
<td>
3
</td>
</tr>
</tbody>
</table>
<dd>
<br/>
需要5秒的奶牛1坐下来，10秒奶牛2坐下来，总共需要10秒
</dd>
</dl>
<p>
这一共花了1 + 5 + 3 + 10 = 19秒。
</p>
<p align="center">
 
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
