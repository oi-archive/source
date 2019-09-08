# 题目描述


<p style="text-align:left;" align="left">
	<b><span style="font-family:Microsoft YaHei;font-size:12pt;">问题描述（背景）：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">位于郊区的动物园很早就采用了当时先进的自动化管理设施对动物进行管理。但是由于当时的系统没有考虑</span><span style="font-family:Microsoft YaHei;">2000</span><span style="font-family:Microsoft YaHei;">年问题，使得管理人员十分担心。虽然采取了很多防范措施，系统还是在世纪之交出现了一些</span><span style="font-family:Microsoft YaHei;">BUG</span><span style="font-family:Microsoft YaHei;">，部分动物的笼子门自动打开了，关在里面的动物都跑出来了。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">幸好动物园已经关闭，</span><u><span style="font-family:Microsoft YaHei;">动物不会跑出动物园</span></u><span style="font-family:Microsoft YaHei;">。警长</span></span><span style="font-family:Microsoft YaHei;">Still</span><span style="font-family:Microsoft YaHei;">接到报警后率领一支干警奔赴现场。这时动物已经跑出了笼子，所以干警们花了很多时间才控制住了局势，所有的动物都己经送到动物园的广场。但是此时有一个棘手的问题，由于系统完全崩溃，无法得知动物是从哪个笼子里面跑出来的。此时，干警们记得动物的一些行动，都是如下的形式：</span> 
</p>
<p style="text-align:center;text-indent:21pt;" align="center">
	<span style="font-family:Microsoft YaHei;">第</span><span style="font-family:Microsoft YaHei;">t</span><span style="font-family:Microsoft YaHei;">分钟看到某某动物在某个位置</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">Still</span><span style="font-family:Microsoft YaHei;">希望通过这些零碎的信息得到动物是从哪个笼子跑出来的。</span> 
</p>
<p>
	<span></span> 
</p>
<p style="text-align:left;" align="left">
	<b><span style="font-family:Microsoft YaHei;font-size:12pt;">任务：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="margin-left:21pt;">
	<span style="font-family:Microsoft YaHei;">根据给出的信息，编程求出每个动物的笼子的位置。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">动物园的地形描述为一个</span><span style="font-family:Microsoft YaHei;">n * n</span><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">的网格，一个格子可以是</span><u><span style="font-family:Microsoft YaHei;">建筑物</span></u><span style="font-family:Microsoft YaHei;">或者</span><u><span style="font-family:Microsoft YaHei;">平地</span></u><span style="font-family:Microsoft YaHei;">。笼子的位置只可能在平地，动物也只在平地运动。每种动物的奔跑速度不一样，例如老虎一分钟可以跑</span></span><span style="font-family:Microsoft YaHei;">5</span><span style="font-family:Microsoft YaHei;">个格子，猫一分钟只可以跑</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">个格子等等。以下是一个例子（其中阴影部分是建筑物）：</span> 
</p>
<p>
	<span></span> 
</p>
<table style="border-collapse:collapse;" border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span style="font-family:Microsoft YaHei;">笼子</span> 
				</p>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
		</tr>
		<tr>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td style="background:#e5e5e5;" width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td style="background:#e5e5e5;" width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td style="background:#e5e5e5;" width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
		</tr>
		<tr>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
		</tr>
		<tr>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td style="background:#e5e5e5;" width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td style="background:#e5e5e5;" width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td style="background:#e5e5e5;" width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
		</tr>
		<tr>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span style="font-family:Microsoft YaHei;">笼子</span> 
				</p>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
			<td width="44">
				<p style="text-align:center;" align="center">
					<span></span> 
				</p>
<br/>
			</td>
		</tr>
	</tbody>
</table>
<p style="text-indent:24pt;">
	<u><span style="font-family:Microsoft YaHei;">每个笼子只关一只动物，不同的笼子关不同的动物。不同的笼子可能在同一个格子里</span></u><span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p>
	<span></span> 
</p>
<p style="text-align:left;" align="left">
	<b><span style="font-family:Microsoft YaHei;font-size:12pt;">输入格式</span></b><b><span style="font-size:12pt;font-family:Microsoft YaHei;">(</span><span style="font-family:Microsoft YaHei;">sample.in)</span></b><b><span style="font-family:Microsoft YaHei;font-size:12pt;">：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">第一行为自然数</span><span style="font-family:Microsoft YaHei;">n</span><span style="font-family:Microsoft YaHei;">，表示网格的边长</span><span style="font-family:Microsoft YaHei;">(n &lt;= 100)</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">以下</span><span style="font-family:Microsoft YaHei;">n</span><span style="font-family:Microsoft YaHei;">行为一个</span><span style="font-family:Microsoft YaHei;">n*n</span><span style="font-family:Microsoft YaHei;">的字符串矩阵，表示动物园的地形。其中</span><span style="font-family:Microsoft YaHei;">’.’</span><span style="font-family:Microsoft YaHei;">表示空地，</span><span style="font-family:Microsoft YaHei;">’*’</span><span style="font-family:Microsoft YaHei;">表示建筑物。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">接着一行是自然数</span><span style="font-family:Microsoft YaHei;">p</span><span style="font-family:Microsoft YaHei;">，表示笼子的数目（同时也是动物的数目）。</span><span style="font-family:Microsoft YaHei;">P &lt;= 100</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">以下</span><span style="font-family:Microsoft YaHei;">p</span><span style="font-family:Microsoft YaHei;">行，每行两个自然数</span><span style="font-family:Microsoft YaHei;">Row, Col</span><span style="font-family:Microsoft YaHei;">，表示一个笼子处于网格的第</span><span style="font-family:Microsoft YaHei;">Row</span><span style="font-family:Microsoft YaHei;">行，第</span><span style="font-family:Microsoft YaHei;">Col</span><span style="font-family:Microsoft YaHei;">列。</span><span><span style="font-family:Microsoft YaHei;">Row &lt;= n</span><span> </span><span style="font-family:Microsoft YaHei;">Col&lt;= n</span></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">以下</span><span style="font-family:Microsoft YaHei;">p</span><span style="font-family:Microsoft YaHei;">行，每行一个整数</span><span style="font-family:Microsoft YaHei;">Vi</span><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">，</span><u><span style="font-family:Microsoft YaHei;">依次</span></u><span style="font-family:Microsoft YaHei;">表示编号为</span></span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">的动物的速度（格子</span><span style="font-family:Microsoft YaHei;">/</span><span style="font-family:Microsoft YaHei;">分钟），每个动物用它的编号表示。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">接着一行是自然数</span><span style="font-family:Microsoft YaHei;">r</span><span style="font-family:Microsoft YaHei;">，表示干警们提供的信息数目。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">以下</span><span style="font-family:Microsoft YaHei;">r</span><span style="font-family:Microsoft YaHei;">行，每行</span><span style="font-family:Microsoft YaHei;">4</span><span style="font-family:Microsoft YaHei;">个自然数，</span><span style="font-family:Microsoft YaHei;">t, Row, Col, j</span><span style="font-family:Microsoft YaHei;">，表示第</span><span style="font-family:Microsoft YaHei;">t</span><span style="font-family:Microsoft YaHei;">分钟在网格的</span><span style="font-family:Microsoft YaHei;">(Row, Col)</span><span style="font-family:Microsoft YaHei;">位置看到动物</span><span style="font-family:Microsoft YaHei;">j .</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">具体格式参照样例。</span> 
</p>
<p>
	<span></span> 
</p>
<p style="text-align:left;" align="left">
	<b><span style="font-family:Microsoft YaHei;font-size:12pt;">输出格式</span></b><b><span style="font-size:12pt;font-family:Microsoft YaHei;">(</span></b><span style="font-family:Microsoft YaHei;">smple.out)</span><b><span style="font-family:Microsoft YaHei;font-size:12pt;">：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">输出任意一个可行解。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">包括</span><span style="font-family:Microsoft YaHei;">p</span><span style="font-family:Microsoft YaHei;">行，每行</span><span style="font-family:Microsoft YaHei;">3</span><span style="font-family:Microsoft YaHei;">个整数</span><span style="font-family:Microsoft YaHei;">i Row Col</span><span style="font-family:Microsoft YaHei;">，表示动物</span><span style="font-family:Microsoft YaHei;">i</span><span style="font-family:Microsoft YaHei;">原来在格子</span><span style="font-family:Microsoft YaHei;">(Row,Col)</span><span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;font-size:12pt;">输入输出样例：</span><span style="font-size:12pt;"></span> 
</p>
<div align="center">
	<table style="border-collapse:collapse;" border="1" cellpadding="0" cellspacing="0">
		<tbody>
			<tr>
				<td style="background:#e5e5e5;" valign="top" width="284">
					<p>
						<span style="font-family:Microsoft YaHei;">Sample.In</span> 
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="284">
					<p>
						<span style="font-family:Microsoft YaHei;">5</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">.....</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">.***.</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">.....</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">.***.</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">.....</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">2</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">1 3</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">5 2</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">1</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">2</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">2</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">5 3 1 2</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">4 5 5 1</span> 
					</p>
					<p>
						<span></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td style="background:#e5e5e5;" valign="top" width="284">
					<p>
						<span style="font-family:Microsoft YaHei;">Sample.Out</span> 
					</p>
				</td>
			</tr>
			<tr>
				<td valign="top" width="284">
					<p>
						<span style="font-family:Microsoft YaHei;">1 5 2</span> 
					</p>
					<p>
						<span style="font-family:Microsoft YaHei;">2 1 3</span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</div>
<p>
	<span></span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">注：对于特定的数据可能有多解，输出任意一解即可。</span> 
</p>
<p>
	<span></span> 
</p>
