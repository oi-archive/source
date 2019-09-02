

# </span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">题目描述</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">


	<p style="text-indent:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">最近，<span>RCDH</span><span>研究外星人的交流方式很特别。它们会设置一个交流网。网络由</span><span>n</span><span>个站点组成，用双向的线连接。两个站点之间最多只能有一条线直接连接，同时每个站点最多只能和</span><span>10</span><span>个站点直接连接，但是任意两个站点之间必须存在一条路径将它们连接一起。每条传输线都有一个固定的传输速度。</span><span>L</span><span>（</span><span>V</span><span>，</span><span>W</span><span>）表示站点</span><span>V</span><span>和</span><span>W</span><span>之间的最短路径长度，且对任意的</span><span>V</span><span>有</span><span>L</span><span>（</span><span>V</span><span>，</span><span>V</span><span>）</span><span>=0</span><span>。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	
# 输人格式


	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">第一行两个整数<span>n</span><span>和</span><span>m</span><span>。</span><span>n</span><span>表示站点的数量，</span><span>m</span><span>表示传输线的数量。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">接下来<span>n</span><span>行，每行有一个整数，第</span><span>I</span><span>行的整数为</span><span>R</span><span>（</span><span>I</span><span>），表示第</span><span>I</span><span>个站点的</span><span>Imp</span><span>。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">接下来<span>m</span><span>行，每行表示各传输线的信息，包含</span><span>3</span><span>个整数</span><span>a</span><span>，</span><span>b</span><span>，</span><span>t</span><span>，</span><span>a</span><span>和</span><span>b</span><span>是传输线所连接的两个站点的编号，</span><span>t</span><span>是传输线的长度。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	
# 输出格式


	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">一个整数，表示所有站点存储的数据总量，即│<span>B</span><span>（</span><span>V</span><span>）│之和。</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	
# 输入样例


	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">6 5</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">4</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">3</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">2</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">4</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1 2 1</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">2 3 1</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">3 4 1</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">4 5 1</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p style="margin-left:21.0000pt;">
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">5 6 1</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	
# 输</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">出</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">样例


	<p style="margin-left:21.0000pt;text-align:justify;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">17</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	
# </span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">数据规模</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">


	<p>
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">    对于<span>100%</span><span>的数据</span></span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">    1&lt;=n&lt;=30000</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">    1&lt;=m&lt;=5n</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">    1&lt;=R(i)&lt;=10</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">    1&lt;=t&lt;=1000</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">    1&lt;=a,b&lt;=n</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">    a<span>≠</span><span>b</span></span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
	</p>
</div>
