# 题目描述


<table style="padding:0pt 5.4pt;border-collapse:collapse;">
	<tbody>
		<tr>
			<td width="111" valign="top" style="background:#F79646;border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16pt;font-weight:bold;">Problem </span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16pt;font-weight:bold;">4</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="552" valign="top" style="background:#F79646;border:1pt solid #F9B074;">
				<p>
					<span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16pt;font-weight:bold;">伊吹萃香</span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16pt;font-weight:bold;">(</span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16pt;font-weight:bold;">suika.</span><span style="color:#FFFFFF;font-family:Microsoft YaHei;font-size:16pt;font-weight:bold;">cpp/c/pas)</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;font-weight:bold;">题目描述</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">在幻想乡，<a href="http://wiki.touhou8.com/index.php?doc-view-108.html" target="_blank">伊吹萃香（いぶき すいか）</a>是能够控制物体密度的鬼王。因为能够控制密度，所以萃香能够制造白洞和黑洞，并可以随时改变它们。某一天萃香闲着无聊，在妖怪之山上设置了一些白洞或黑洞，由于引力的影响，给妖怪们带来了很大的麻烦。于是他们决定找出一条消耗体力最少的路，来方便进出。已知妖怪之山上有</span><span style="font-family:Microsoft YaHei;">N</span><span style="font-family:Microsoft YaHei;">个路口</span><span style="font-family:Microsoft YaHei;">(</span><span style="font-family:Microsoft YaHei;">编号</span><span style="font-family:Microsoft YaHei;">1..N)</span><span style="font-family:Microsoft YaHei;">，每个路口都被萃香设置了一定质量白洞或者黑洞。原本在各个路口之间有</span><span style="font-family:Microsoft YaHei;">M</span><span style="font-family:Microsoft YaHei;">条单向路，走过每一条路需要消耗一定量的体力以及</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">个单位的时间。由于白洞和黑洞的存在，走过每条路需要消耗的体力也就产生了变化，假设一条道路两端路口黑白洞的质量差为</span><span style="font-family:Microsoft YaHei;">delta</span><span style="font-family:Microsoft YaHei;">：</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">1. </span><span style="font-family:Microsoft YaHei;">从有白洞的路口走向有黑洞的路口，消耗的体力值减少</span><span style="font-family:Microsoft YaHei;">delta</span><span style="font-family:Microsoft YaHei;">，若该条路径消耗的体力值变为负数的话，取为</span><span style="font-family:Microsoft YaHei;">0</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">2. </span><span style="font-family:Microsoft YaHei;">从有黑洞的路口走向有白洞的路口，消耗的体力值增加</span><span style="font-family:Microsoft YaHei;">delta</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">3. </span><span style="font-family:Microsoft YaHei;">如果路口两端均为白洞或黑洞，消耗的体力值无变化。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">由于光是放置黑洞白洞不足以体现萃香的强大，所以她决定每过</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">个单位时间，就把所有路口的白洞改成黑洞，黑洞改成白洞。当然在走的过程中你可以选择在一个路口上停留</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">个单位的时间，如果当前路口为白洞，则不消耗体力，否则消耗</span><span style="font-family:Microsoft YaHei;">s[i]</span><span style="font-family:Microsoft YaHei;">的体力。现在请你计算从路口</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">走到路口</span><span style="font-family:Microsoft YaHei;">N</span><span style="font-family:Microsoft YaHei;">最小的体力消耗。保证一定存在道路从路口</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">到路口</span><span style="font-family:Microsoft YaHei;">N</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #F9B074;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;font-weight:bold;">输入格式</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">第</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">行：</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">个正整数</span><span style="font-family:Microsoft YaHei;">N, M</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">第</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">行：</span><span style="font-family:Microsoft YaHei;">N</span><span style="font-family:Microsoft YaHei;">个整数，第</span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">个数为</span><span style="font-family:Microsoft YaHei;">0</span><span style="font-family:Microsoft YaHei;">表示第</span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">个路口开始时为白洞，</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">表示黑洞</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">第</span><span style="font-family:Microsoft YaHei;">3</span><span style="font-family:Microsoft YaHei;">行：</span><span style="font-family:Microsoft YaHei;">N</span><span style="font-family:Microsoft YaHei;">个整数，第</span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">个数表示第</span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">个路口设置的白洞或黑洞的质量</span><span style="font-family:Microsoft YaHei;">w[i]</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">第</span><span style="font-family:Microsoft YaHei;">4</span><span style="font-family:Microsoft YaHei;">行：</span><span style="font-family:Microsoft YaHei;">N</span><span style="font-family:Microsoft YaHei;">个整数，第</span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">个数表示在第</span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">个路口停留消耗的体力</span><span style="font-family:Microsoft YaHei;">s[i]</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">第</span><span style="font-family:Microsoft YaHei;">5..M+4</span><span style="font-family:Microsoft YaHei;">行：每行</span><span style="font-family:Microsoft YaHei;">3</span><span style="font-family:Microsoft YaHei;">个整数，</span><span style="font-family:Microsoft YaHei;">u, v, k</span><span style="font-family:Microsoft YaHei;">，表示在没有影响的情况下，从路口</span><span style="font-family:Microsoft YaHei;">u</span><span style="font-family:Microsoft YaHei;">走到路口</span><span style="font-family:Microsoft YaHei;">v</span><span style="font-family:Microsoft YaHei;">需要消耗</span><span style="font-family:Microsoft YaHei;">k</span><span style="font-family:Microsoft YaHei;">的体力。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;font-weight:bold;">输出格式</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">第</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">行：</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">个整数，表示消耗的最小体力</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #F9B074;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;font-weight:bold;">输入样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">4 5</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">1 0 1 0</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">10 10 100 10</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">5 20 15 10</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">1 2 30</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">2 3 40</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">1 3 20</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">1 4 200</span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">3 4 200</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;font-weight:bold;">输出样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">130</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="border:1pt solid #F9B074;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;font-weight:bold;">数据范围</span><span style="font-size:16pt;font-weight:bold;"></span> 
				</p>
			</td>
			<td width="581" valign="top" style="border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:Microsoft YaHei;">30%</span><span style="font-family:Microsoft YaHei;">的数据：</span><span style="font-family:Microsoft YaHei;">1 &lt;= N &lt;= 100, 1 &lt;= M &lt;= 500</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:Microsoft YaHei;">60%</span><span style="font-family:Microsoft YaHei;">的数据：</span><span style="font-family:Microsoft YaHei;">1 &lt;= N &lt;= 1,000, 1 &lt;= M &lt;= 5,000</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:Microsoft YaHei;">100%</span><span style="font-family:Microsoft YaHei;">的数据：</span><span style="font-family:Microsoft YaHei;">1 &lt;= N &lt;= 5,000, 1 &lt;= M &lt;= 30,000</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">其中</span><span style="font-family:Microsoft YaHei;">20%</span><span style="font-family:Microsoft YaHei;">的数据为</span><span style="font-family:Microsoft YaHei;">1 &lt;= N &lt;= 3000</span><span style="font-family:Microsoft YaHei;">的链</span></span><span style="font-size:10.5pt;"></span> 
				</p>
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;">1 &lt;= u,v &lt;= N, 1 &lt;= k,w[i],s[i] &lt;= 200</span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td width="82" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;">
				<p>
					<span style="font-family:Microsoft YaHei;font-size:10.5pt;font-weight:bold;">样例说明</span><span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"=""></span> 
				</p>
			</td>
			<td width="581" valign="top" style="background:#FDE4D0;border:1pt solid #F9B074;" colspan="2">
				<p>
					<span style="font-size:10.5pt;"><span style="font-family:Microsoft YaHei;">按照</span><span style="font-family:Microsoft YaHei;">1 -&gt; 3 -&gt; 4</span><span style="font-family:Microsoft YaHei;">的路线。</span></span><span style="font-size:10.5pt;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<br/>
