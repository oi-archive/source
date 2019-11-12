# 题目描述


<p>
USACO/cryptcow(译 by Zen)
</p>
<p>
<span>描述</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p align="left">
<span style="font-family:&#39;Times New Roman&#39;;">农夫布朗的牧场上的篱笆已经失去控制了。它们分成了1~200英尺长的线段。只有在线段的端点处才能连接两个线段，有时给定的一个端点上会有两个以上的篱笆。结果篱笆形成了一张网分割了布朗的牧场。布朗想将牧场恢复原样，出于这个考虑，他首先得知道牧场上哪一块区域的周长最小。<br/>
布朗将他的每段篱笆从1到N进行了标号（N=线段的总数）。他知道每段篱笆的有如下属性：</span> 
</p>
<ul>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">该段篱笆的长度</span> 
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">该段篱笆的一端所连接的另一段篱笆的标号</span> 
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">该段篱笆的另一端所连接的另一段篱笆的标号</span> 
</li>
</ul>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">幸运的是，没有篱笆连接它自身。<br/>
对于一组有关篱笆如何分割牧场的数据，写一个程序来计算出所有分割出的区域中最小的周长。<br/>
例如，标号1~10的篱笆由下图的形式组成（下面的数字是篱笆的标号）：<br/>
　</span> 
</p>
<pre><span style="font-family:宋体;font-size:small;"> 1
   +---------------+
   |             /|
  2| 7          / |
   |           /  |
   +---+       /   |6
   | 8       /10  |
  3|     9  /     |
   |       /      |
   +-------+-------+
       4       5</span><span style="font-family:&#39;Times New Roman&#39;;font-size:small;"> </span></pre>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">上图中周长最小的区域是由2，7，8号篱笆形成的。<br/>
<span></span></span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><span>格式</span></span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"> </span> 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: fence6</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file fence6.in)</span> 
</h3>
<table border="1">
<tbody>
<tr>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">第1行:</span> 
</td>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">N (1 &lt;= N &lt;= 100)</span> 
</td>
</tr>
<tr>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">第2行到第3*N+1行: </span> 
</td>
<td>
<span style="font-family:&#39;Times New Roman&#39;;">每三行为一组，共N组信息:</span> 
<ul>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">每组信息的第1行有4个整数: s, 这段篱笆的标号(1 &lt;= s &lt;= N);</span>
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;"> Ls, the这段篱笆的长度 (1 &lt;= Ls &lt;= 255);</span>
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;"> N1s (1 &lt;= N1s &lt;= 8) 与本段篱笆的一端所相邻的篱笆的数量;</span>
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;"> and N2s与本段篱笆的另一端所相邻的篱笆的数量。 (1 &lt;= N2s &lt;= 8).  </span> 
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">每组信息的的第2行有 N1s个整数, 分别描述与本段篱笆的一端所相邻的篱笆的标号。</span> 
</li>
<li>
<span style="font-family:&#39;Times New Roman&#39;;">每组信息的的第3行有N2s个整数, 分别描述与本段篱笆的另一端所相邻的篱笆的标号。</span> 
</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>
<b><span style="font-family:&#39;Times New Roman&#39;;font-size:medium;">OUTPUT FORMAT(file fence6.out)</span></b> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">输出的内容为单独的一行，用一个整数来表示最小的周长。</span> 
</p>
<p>
<b><span style="font-family:&#39;Times New Roman&#39;;font-size:medium;">SAMPLE INPUT (file fence6.in) </span></b> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">10<br/>
1 16 2 2<br/>
2 7<br/>
10 6<br/>
2 3 2 2<br/>
1 7<br/>
8 3<br/>
3 3 2 1<br/>
8 2<br/>
4<br/>
4 8 1 3<br/>
3<br/>
9 10 5<br/>
5 8 3 1<br/>
9 10 4<br/>
6<br/>
6 6 1 2 <br/>
5 <br/>
1 10<br/>
7 5 2 2 <br/>
1 2<br/>
8 9<br/>
8 4 2 2<br/>
2 3<br/>
7 9<br/>
9 5 2 3<br/>
7 8<br/>
4 5 10<br/>
10 10 2 3<br/>
1 6<br/>
4 9 5</span> 
</p>
<p>
<br/>
</p>
<p>
<b><span style="font-family:&#39;Times New Roman&#39;;font-size:medium;">SAMPLE OUTPUT (file fence6.out)</span></b> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">12</span> 
</p>
<span style="font-family:&#39;Times New Roman&#39;;"></span> 
<p>
<br/>
</p>
<span></span> 
<p>
<br/>
</p>
<p>
<br/>
</p>
