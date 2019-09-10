# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">背景 Background</span> 
</h3>
<div>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（喵星人rainbow和freda同心协力击退了汪星人的入侵，不幸的是，汪星人撤退之前给它们制造了一片幻象迷宫。）</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> freda：呜呜，肿么办啊……</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> rainbow：momo...我们一定能走出去的！</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> freda：嗯，+U+U！</span> 
</div>
<div>
	<h3>
		<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">描述 Description</span> 
	</h3>
	<p>
		<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">幻象迷宫可以认为是无限大的，不过它由若干个N*M的矩阵重复组成。矩阵中有的地方是道路，用&#39;.&#39;表示；有的地方是墙，用&#39;#&#39;表示。rainbow和freda所在的位置用&#39;S&#39;表示。也就是对于迷宫中的一个点(x,y)，如果(x mod n,y mod m)是&#39;.&#39;或者&#39;S&#39;，那么这个地方是道路；如果(x mod n,y mod m)是&#39;#&#39;，那么这个地方是墙。rainbow和freda可以向上下左右四个方向移动，当然不能移动到墙上。</span> 
	</p>
	<p>
		<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">请你告诉rainbow和freda，它们能否走出幻象迷宫（如果它们能走到距离起点无限远处，就认为能走出去）。如果不能的话，rainbow就只好启动城堡的毁灭程序了……当然不到万不得已，他不想这么做。。。</span> 
	</p>
	<p>
		<br/>
	</p>
	<div>
		<div>
			<div>
				<br/>
				<div>
				</div>
				<div>
				</div>
			</div>
			<div>
			</div>
			<div>
				<h3>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入格式 Input Format</span> 
				</h3>
				<div>
					<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入包含多组数据，以EOF结尾。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 每组数据的第一行是两个整数N、M。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 接下来是一个N*M的字符矩阵，表示迷宫里(0,0)到(n-1,m-1)这个矩阵单元。</span> 
				</div>
			</div>
			<div>
			</div>
			<div>
				<div>
				</div>
				<div>
				</div>
				<div>
				</div>
			</div>
		</div>
		<div>
		</div>
	</div>
	<div>
		<div>
			<div>
			</div>
			<div>
			</div>
			<div>
			</div>
		</div>
		<div>
		</div>
		<div>
			<h3>
				<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出格式 Output Format</span> 
			</h3>
			<div>
				<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于每组数据，输出一个字符串，Yes或者No。</span> 
			</div>
		</div>
	</div>
	<p>
		<br/>
	</p>
</div>
<div>
</div>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入数据：</span> 
</h3>
<pre>5 4
##.#
##S#
#..#
#.##
#..#
5 4
##.#
##S#
#..#
..#.
#.##
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出数据：</span> 
</h3>
<pre>Yes
No
</pre>
<div>
	<div>
		<div>
			<h3>
				<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">时间限制 Time Limitation</span> 
			</h3>
			<div>
				<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">每个测试点1s</span> 
			</div>
		</div>
		<div>
		</div>
		<div>
			<div>
			</div>
			<div>
			</div>
			<div>
			</div>
		</div>
	</div>
	<div>
	</div>
</div>
<div>
	<div>
		<div>
		</div>
		<div>
		</div>
		<div>
		</div>
	</div>
	<div>
	</div>
	<div>
		<h3>
			<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">注释 Hint</span> 
		</h3>
		<div>
			<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于30%的数据，N,M&lt;=20</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 对于50%的数据，N.M&lt;=100.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 对于100%的数据，N,M&lt;=1500，每个测试点不超过10组数据.</span> 
		</div>
	</div>
</div>
<p>
	<br/>
</p>
<div>
	<div>
	</div>
</div>
<p>
	<br/>
</p>
