# 题目描述


<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>的业余生活中，有一项是玩滚玻璃球游戏。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">某天，小<span>x</span><span>想到了一种很无趣的玩法，当然，这种玩法就是为了玩看题的你们。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>首先建立了一个单向轨道，这个单向轨道可以抽象成一个有向图，每个顶点的出度都是</span><span>1</span><span>，也就是由每个点出发，只有一条边连向其他的点。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>的游戏最初规则是这样的：让玻璃球从某一个点出发，沿着有向边的方向，移动到它的下一个顶点，如果还能移动，就继续移动，直到没有相邻的边，当然会存在在一个环里不停运动的情况。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">为了增加难度，小<span>x</span><span>决定将游戏规则增强，他会提出一系列问题，让你回答：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:48.0000pt;text-indent:-27.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1） </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">格式：<span>1 X.</span><span>查询玻璃球由编号为</span><span>X</span><span>的点出发，最终在哪个点停下来，如果能停下来，输出最后的点的编号，如果停不下来，输出</span></span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">”</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">CIKLUS</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">”</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">.</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:48.0000pt;text-indent:-27.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">2） </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">格式：<span>2 X.</span><span>删除由</span><span>X</span><span>出发的那条有向边。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">第一行包含一个正整数</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">N</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">（</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1&lt;=N&lt;=300000</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">）</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">,</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">表示图的顶点数。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">第二行包含由空格隔开</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">N</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个正整数，第</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">i</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个数表示从</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">i</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">顶点可以通过出边到达的定点编号，</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">0</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">表示该点没有出边。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">接下来的一行包含</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个整数</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">Q</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">（</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1&lt;=Q&lt;=300000</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">）</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">,</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">表示询问的次数。</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">再接下来Q行，每行表示一次查询，格式如题目描述。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">对于第</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">类询问，输出玻璃球停止时所在顶点编号</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">,</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">每行</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">1</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">个，按照查询的顺序输出。如果玻璃球无法停止，输出</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">”</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">CIKLUS</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;">”</span><span style="color:#000000;font-size:10.5000pt;font-family:&#39;宋体&#39;;background:#FFFFFF;">即可<span>.</span></span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;background:#FFFFFF;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>1</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
<tbody>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">marbles</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">marbles</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">3 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">2 3 1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">7 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 2 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">2 1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 2 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">2 2 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 2</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">CIKLUS </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">CIKLUS </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>2</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
<tbody>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">marbles</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">marbles</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">5 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">0 3 5 3 4 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">6 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 2 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">2 4 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 2 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">2 3 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="282">
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">1 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">CIKLUS </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">4 </span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<span style="font-size:16.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【数据范围】 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   40% <span>数据保证  </span><span>N&lt;=100,  Q&lt;=1000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:16.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span> 
</p>
