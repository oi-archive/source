# 题目描述


<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">题目背景：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">幻想乡的亡灵公主，西行寺幽幽子，在幻想乡很受欢迎，经常有妖怪来拜访她，但是幽幽子并不喜欢被打扰，她希望从白玉楼出发，散步之后再回到白玉楼，同时路上遇到的妖怪越少越好<span>(</span>有趣的是道路两边的妖怪数量并不相同，分别从两个方向经过同一条道路遇到的妖怪数量是不同的<span>)</span>。当然，作为冥界的公主，她是不会重复经过同一条道路的。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">问题描述：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">给定一个有<span> n </span>个点<span>m</span>条无向边的图，每条无向边最多只能经过一次。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于边<span>(ui,
vi), </span>从<span> ui </span>到<span> vi </span>的代价为<span> ai</span>，从<span> vi </span>到<span> ui </span>的代价为<span> bi</span>，其中<span>ai</span>和<span>bi</span>不一定相等。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">求一个包含<span> 1 </span>号点的有向环，使得环上代价之和最小。<span>(</span><u>保证图中没有重边和自环</u>。<span>)</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">输入格式：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">第一行两个个正整数<span> n</span>，<span>m</span>，点数和边数。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">接下来<span> m </span>行，每行四个正整数，<span>ui</span>，<span>vi</span>，<span>ai</span>，<span>bi</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">从<span> ui </span>到<span> vi </span>的代价为<span> ai</span>，从<span> vi </span>到<span> ui </span>的代价为<span> bi</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">输出格式：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">输出一行，一个整数，如果有解输出最小代价，否则输出<span>&#39;&#39;-1&#39;&#39;(</span>不含引号<span>)</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;"> </span></b> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;"> </span></b> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">样例数据<span>1</span>：<span></span></span></b> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="643">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:Ubuntu;">zaw.in</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:Ubuntu;">zaw.out</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">3 3</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">1 2 4 3</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">2 3 4 2</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">1 3 1 1</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">6</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;"> </span></b> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;"> </span></b> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">样例数据<span>2</span>：<span></span></span></b> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="643">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:Ubuntu;">zaw.in</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:Ubuntu;">zaw.out</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">3 2</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">1 2 12 5</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">3 2 10 5</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">-1</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">数据范围：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于前<span> 15% </span>的数据，<span>3 &lt;= n &lt;= 20, 3 &lt;= m &lt;= 20</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于前<span> 30% </span>的数据，<span>3 &lt;= n &lt;= 150, 3 &lt;= m &lt;= 2500</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于前<span> 70% </span>的数据，<span>3 &lt;= n &lt;= 5000, 3 &lt;= m &lt;= 10^4</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于<span>100% </span>的数据，<span>  3 &lt;= n
&lt;= 3*10^4, 3 &lt;= m &lt;= 10^5</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       1&lt;=
ui, vi &lt;= n</span><span style="font-family:文泉驿微米黑;">，<span>1 &lt;= ai, bi &lt;= 10^4</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><u><span style="font-family:文泉驿微米黑;">保证图中没有重边</span></u><span style="font-family:文泉驿微米黑;">，即不存在<span> i &lt;&gt; j</span>，使得<span> ui = uj</span>，<span>vi = vj</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><u><span style="font-family:文泉驿微米黑;">保证图中没有自环</span></u><span style="font-family:文泉驿微米黑;">，即<span>ui
&lt;&gt; vi</span>。<span></span></span> 
</p>
