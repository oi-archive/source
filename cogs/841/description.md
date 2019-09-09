# 题目描述


<p>
	<span style="font-family:宋体;">【问题描述】</span><span style="font-family:;"></span> 
</p>
<p>
	<span style="font-family:;"><span>    </span></span><span style="font-family:宋体;">小</span><span style="font-family:;">x</span><span style="font-family:宋体;">在玩一款塔防类游戏。游戏的规则如下：</span><span style="font-family:;"></span> 
</p>
<p style="margin-left:39.0pt;text-indent:-18.0pt;">
	<span style="font-family:;"><span>1）<span> </span></span></span><span style="font-family:宋体;">整个地图由</span><span style="font-family:;">N</span><span style="font-family:宋体;">个交汇点，</span><span style="font-family:;">M</span><span style="font-family:宋体;">条双向的道路组成；</span><span style="font-family:;"></span> 
</p>
<p style="margin-left:39.0pt;text-indent:-18.0pt;">
	<span style="font-family:;"><span>2）<span> </span></span></span><span style="font-family:宋体;">怪物出现的地点为</span><span style="font-family:;">S</span><span style="font-family:宋体;">，终点为</span><span style="font-family:;">T</span><span style="font-family:宋体;">；</span><span style="font-family:;"></span> 
</p>
<p style="margin-left:39.0pt;text-indent:-18.0pt;">
	<span style="font-family:;"><span>3）<span> </span></span></span><span style="font-family:宋体;">怪物通过每段小路都要一定的时间；</span><span style="font-family:;"></span> 
</p>
<p style="text-indent:17.85pt;">
	<span style="font-family:宋体;">这个游戏的任务不是把怪物消灭，而是延缓怪物到达终点的时间。小</span><span style="font-family:;">x</span><span style="font-family:宋体;">唯一的道具是路障，一个路障可以减缓通过这段路的所有怪物一个单位时间。所以怪物从起点到达终点的时间就是</span><span style="font-family:;"> </span><b><span style="font-family:宋体;">没有路障他们通过所有路径经过的时间</span></b><span style="font-family:;">+ </span><b><span style="font-family:宋体;">路径上</span></b><b><span style="font-family:;"> </span></b><b><span style="font-family:宋体;">路障的个数</span></b><span style="font-family:宋体;">。</span><span style="font-family:;"></span> 
</p>
<p style="text-indent:17.85pt;">
	<span style="font-family:宋体;">游戏中的怪物是很聪明的，他们会在出发前侦查到每段路上的路障个数，然后选择总时间最短的路径。</span><span style="font-family:;"></span> 
</p>
<p style="text-indent:17.9pt;">
	<b><span style="font-family:宋体;">小</span></b><b><span style="font-family:;">x</span></b><b><span style="font-family:宋体;">现在想知道<span style="color:blue;">最少</span>需要多少个路障，才能使得怪物从起点到终点的时间<span style="color:blue;">变长</span>。</span></b><b><span style="font-family:;"></span></b> 
</p>
<p>
	<span style="font-family:宋体;">【输入】</span><span></span> 
</p>
<p>
	<span><span>       </span></span><span style="font-family:宋体;">第一行：</span><span>N</span><span style="font-family:宋体;">，</span><span>M</span><span style="font-family:宋体;">，</span><span>S</span><span style="font-family:宋体;">和</span><span>T</span><span style="font-family:宋体;">，具体含义如题目描述。</span><span>N</span><span style="font-family:宋体;">个交汇点的编号范围是</span><span>1..N</span><span style="font-family:宋体;">。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:宋体;">接下来</span><span>M</span><span style="font-family:宋体;">行，每行三个整数</span><span>A</span><span style="font-family:宋体;">，</span><span>B</span><span style="font-family:宋体;">，</span><span>C</span><span style="font-family:宋体;">。表示</span><span>A</span><span style="font-family:宋体;">到</span><span>B</span><span style="font-family:宋体;">之间有一条小路相连，且通过它需要的时间为</span><span>C</span><span style="font-family:宋体;">。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:宋体;">输入数据保证两点最多只有一条道路相连，且</span><span>S</span><span style="font-family:宋体;">到</span><span>T</span><span style="font-family:宋体;">必然存在路径。</span><span></span> 
</p>
<p>
	<span style="font-family:宋体;">【输出】</span><span></span> 
</p>
<p>
	<span><span>       </span></span><span style="font-family:宋体;">一个整数，表示</span><span>S</span><span style="font-family:宋体;">到</span><span>T</span><span style="font-family:宋体;">之间最短路增长所需要最小的路障的数目。</span><span></span> 
</p>
<p>
	<span style="font-family:宋体;">【输入输出样例</span><span>1</span><span style="font-family:宋体;">】</span><span></span> 
</p>
<table style="border-collapse:collapse;border:none;" border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<span style="font-family:;">defence.in</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<span>defence</span><span style="font-family:;">.out</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<br/>
				</p>
<pre class="prettyprint">5 5 1 5
1 2 1
2 3 3
1 4 2
4 3 2
5 1 1</pre>
				<p>
					<br/>
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<br/>
				</p>
<pre class="prettyprint">1</pre>
				<p>
					<br/>
				</p>
				<p>
					<span style="font-family:;">{</span><span style="font-family:宋体;">起点到终点的最短路是</span><span style="font-family:;">1</span><span style="font-family:宋体;">到</span><span style="font-family:;">5</span><span style="font-family:宋体;">的道路，所以直接一个路障就可以了。</span><span style="font-family:;">}</span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-family:宋体;">【输入输出样例</span><span>2</span><span style="font-family:宋体;">】</span><span></span> 
</p>
<table style="border-collapse:collapse;border:none;" border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<span>defence</span><span style="font-family:;">.in</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<span>defence</span><span style="font-family:;">.out</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<br/>
				</p>
<pre class="prettyprint">6 11 2 5
2 3 1
2 1 4
2 6 2
5 4 11
5 1 16
5 6 18
4 1 5
4 6 7
3 1 3
3 6 1
1 6 2</pre>
				<p>
					<br/>
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<br/>
				</p>
<pre class="prettyprint">3 </pre>
				<p>
					<br/>
				</p>
				<p>
					<span style="font-family:;">{1</span><span style="font-family:宋体;">—</span><span style="font-family:;">5,4</span><span style="font-family:宋体;">—</span><span style="font-family:;">5,6</span><span style="font-family:宋体;">—</span><span style="font-family:;">5 </span><span style="font-family:宋体;">都</span><span style="font-family:;">+1</span><span style="font-family:宋体;">就可满足，当然还会有其他方案。</span><span style="font-family:;">}</span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-family:宋体;">【数据范围】</span><span> </span> 
</p>
<p>
	<span>30%<span>  </span>N&lt;=10,M&lt;=50</span> 
</p>
<p>
	<span>50%<span>  </span>N&lt;=200,M&lt;=100000</span> 
</p>
<p>
	<span>30%<span>  </span>N&lt;=1000,M&lt;=499500<span>  </span>0<c<=1000000.< span=""><span style="font-size:16.0pt;"></span> </c<=1000000.<></span> 
</p>
<span style="font-size:10.5pt;font-family:宋体;"><br/>
</span>
