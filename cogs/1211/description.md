# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    熊大妈的奶牛在时针的带领下，围成了一个圆圈跳舞。由于没有严格的教育，奶牛们之间的间隔不一致。</span> 
</p>
<p>
<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">  </span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">奶牛想知道两只最远的奶牛到底隔了多远。奶牛</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">A</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">到</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">B</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的距离为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">A</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">顺时针走和逆时针走，到达</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">B</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的较短路程。告诉你相邻两个奶牛间的距离，请你告诉奶牛两只最远的奶牛</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">到底隔了多远。</span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">   第一行一个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，表示有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">只奶牛。</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">100000)</span> 
</p>
<p>
<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">  </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">   </span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">～</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N+1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">行，第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">I</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">行有一个数，表示第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">I-1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">头奶牛顺时针到第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">I</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">头奶牛的距离。</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">≤距离≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">maxlongint</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，距离和≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">maxlongint)</span> 
</p>
<span style="font-size:10.5pt;font-family:;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">   </span><span></span></span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">N+l</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行的数表示第</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">头奶牛顺时针到第</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">头奶牛的距离。</span> 
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">一行，表示最大距离。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>5 
1 
2 
3 
4 
5
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>7
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例解析,</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> c</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">irclea.out</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">所有奶牛</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">I</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">到</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">J</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">之间的距离和到达方式（顺为顺时针，逆为逆时针）如下：</span> 
</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td width="37">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">I\J</span> 
</p>
</td>
<td width="69">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</p>
</td>
<td width="81">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
</td>
<td width="82">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</p>
</td>
<td width="77">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4</span> 
</p>
</td>
<td width="65">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span> 
</p>
</td>
</tr>
<tr>
<td width="37">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</p>
</td>
<td width="69">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">O</span> 
</p>
</td>
<td width="81">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 (</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">顺</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">)</span></span> 
</p>
</td>
<td width="82">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3(</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">顺</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">)</span></span> 
</p>
</td>
<td width="77">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（顺）</span><span></span></span> 
</p>
</td>
<td width="65">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
</tr>
<tr>
<td width="37">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
</td>
<td width="69">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="81">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">O</span> 
</p>
</td>
<td width="82">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（顺）</span><span></span></span> 
</p>
</td>
<td width="77">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（顺）</span><span></span></span> 
</p>
</td>
<td width="65">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
</tr>
<tr>
<td width="37">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</p>
</td>
<td width="69">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="81">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="82">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0</span> 
</p>
</td>
<td width="77">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（顺）</span><span></span></span> 
</p>
</td>
<td width="65">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">7</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（顺）</span><span></span></span> 
</p>
</td>
</tr>
<tr>
<td width="37">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4</span> 
</p>
</td>
<td width="69">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="81">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="82">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="77">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0</span> 
</p>
</td>
<td width="65">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4(</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">顺</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">)</span></span> 
</p>
</td>
</tr>
<tr>
<td width="37">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span> 
</p>
</td>
<td width="69">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（顺）</span><span></span></span> 
</p>
</td>
<td width="81">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（顺）</span><span></span></span> 
</p>
</td>
<td width="82">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">7</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="77">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4</span><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（逆）</span><span></span></span> 
</p>
</td>
<td width="65">
<p style="text-align:left;" align="left">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0</span> 
</p>
</td>
</tr>
</tbody>
</table>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">所以，最远的两头奶牛为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">到</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">5</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，距离是</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">7</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">。</span> 
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在此键入。</span> 
</p>
