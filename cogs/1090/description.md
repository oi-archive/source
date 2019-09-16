# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    过年的时候，大人们最喜欢的活动，就是打牌了。xiaomengxian不会打牌，只好坐在一边看着。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     这天，正当一群人打牌打得起劲的时候，突然有人喊道：“这副牌少了几张！”众人一数，果然是少了。于是这副牌的主人得意地说：“这是一幅特制的牌，我知道整副牌每一张的重量。只要我们称一下剩下的牌的总重量，就能知道少了哪些牌了。”大家都觉得这个办法不错，于是称出剩下的牌的总重量，开始计算少了哪些牌。由于数据量比较大，过了不久，大家都算得头晕了。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     这时，xiaomengxian大声说：“你们看我的吧！”于是他拿出笔记本电脑，编出了一个程序，很快就把缺少的牌找了出来。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     如果是你遇到了这样的情况呢？你能办到同样的事情吗？</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    第一行一个整数TotalW，表示剩下的牌的总重量。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     第二行一个整数N（1&lt;=N&lt;=100)<n<=100），表示这副牌有多少张。< span=""><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     接下来N行，每行一个整数Wi（1&lt;=Wi&lt;=1000），表示每一张牌的重量。</span> </n<=100），表示这副牌有多少张。<></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">    如果无解，则输出“0”；如果有多解，则输出“-1”；否则，按照升序输出丢失的牌的编号，相邻两个数之间用一个空格隔开。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>270
4
100
110
170
200
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>2 4
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">各个测试点1s</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Xiaomengxian</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 
	</span></p><table height="0" border="0" cellpadding="0" cellspacing="0" bgcolor="#FFFFFF" style="font-family:&#39;YaHei Consolas Hybrid&#39;, sans-serif;">
		<tbody>
			<tr>
				<td width="502" align="left" valign="top" style="font-family:Tahoma;color:#32656D;">
					<br/>
Sample input #2 <br/>
270 <br/>
4 <br/>
100 <br/>
110 <br/>
160 <br/>
170 <br/>
<br/>
Sample output #2 <br/>
-1 <br/>
<br/>
Sample input #3 <br/>
270 <br/>
4 <br/>
100 <br/>
120 <br/>
160 <br/>
180 <br/>
<br/>
Sample output #3 <br/>
0 
				</td>
			</tr>
		</tbody>
	</table>
<br/>
 
<p></p>
