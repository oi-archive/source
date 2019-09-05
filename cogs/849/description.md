# 题目描述


<div>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">伟大的<span>Farmer John</span><span>要来</span><span>jzyz</span><span>签字卖书了。</span></span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">J</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">zyz<span>的</span><span>oier</span><span>都怀着激动的心情排队去买书。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">作为一件伟大的事情，排队的方式当然不能太简单了。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">排队的第一原则是和谐， <span>oier</span><span>都很兴奋，组织者发现如果某些相邻</span><span>oier</span><span>很熟悉，他们就会大声说话，他们说话的声音与他们熟悉程度成正比，这样就很影响</span><span>Farmer John</span><span>签字的心情。所以我们要让队伍中所有相邻的两个人之间的熟悉程度总和最小。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">为了不让队伍过于凌乱，排队时还要满足以下规则：每个人都有固定的身高<span>H[i]</span><span>，给定一个高度差</span><span>K</span><span>，如果</span><span>H[a]-H[b]</span><span>大于等于</span><span>K</span><span>，那么第</span><span>a</span><span>个人必须在第</span><span>b</span><span>个人的后边。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">此外，为了简化问题，最矮的人将被排在队头。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现在给定所有人的熟悉程度，求出满足高度差的情况下，整个队伍的最小熟悉程度总和。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行两个整数<span>N</span><span>和</span><span>K</span><span>，表示总人数和允许的高度差</span><span>K</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来一行是递增的<span>N</span><span>个整数，表示</span><span>N</span><span>个人的高度</span><span>H[i]</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>N*N</span><span>的整数矩阵</span><span>W</span><span>，</span><span>W[i][j]</span><span>表示第</span><span>i</span><span>个人和第</span><span>j</span><span>个人的熟悉程度，当然</span><span>W</span><span>肯定是对称的，且对角线的值肯定是</span><span>0.</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个整数，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">整个队伍的最小熟悉程度总和</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>1</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
		<tbody>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="282">
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">queuea</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="282">
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">queue</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">a.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="282">
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 8</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1600 1601 1604 1607 1609</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 53 33 37</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 39 0 20</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">53 39 0 56 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">33 0 56 0 36</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">37 20 2 36 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="282">
					<p>
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">38</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例解释】 最优的排队顺序是 <span>1600 1601 1607 1609 1604</span></span><span style="font-size:16.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【数据范围】 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   对于<span>20% </span><span>数据  </span><span>1&lt;=N&lt;=10</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:15.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对于<span>50% </span><span>数据  </span><span>1&lt;=N&lt;=100</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   对于<span>40%</span><span>数据   </span><span>1&lt;=K&lt;=4</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:15.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对于<span>100% </span><span>数据  </span><span>1&lt;=N&lt;=1000  1&lt;=K&lt;=8  1000&lt;=H[i]&lt;=5000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><br/>
</span> 
	</p>
</div>
