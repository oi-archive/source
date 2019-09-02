
<h2 style="text-align:left;" align="left">
	【问题描述】
</h2>

# 输入文件


<div align="center">
	<table style="border:none;" border="1" cellpadding="0" cellspacing="0">
		<tbody>
			<tr>
				<td style="border:solid windowtext 1.0pt;" valign="top" width="449">
					<p style="text-align:left;" align="left">
						<span>N M</span> 
					</p>
					<p style="text-align:left;" align="left">
						<span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">11</span><span style="font-family:;"></span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">12</span><span style="font-family:;"></span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">13</span><span style="font-family:;">⋯⋯</span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">1m</span><span style="font-size:10.5pt;font-family:;"></span><span style="font-family:宋体;"> </span> 
					</p>
					<p style="text-align:left;" align="left">
						<span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">21</span><span style="font-family:;"></span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">22</span><span style="font-family:;"></span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">23</span><span style="font-family:;">⋯⋯</span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">2m</span><span style="font-size:10.5pt;font-family:;"></span><span style="font-family:宋体;"> </span> 
					</p>
					<p style="text-align:left;" align="left">
						<span style="font-family:;">⋯⋯</span><span style="font-size:10.5pt;font-family:;"></span><span style="font-family:宋体;"> </span> 
					</p>
					<p style="text-align:left;" align="left">
						<span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">n1</span><span style="font-family:;"></span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">n2</span><span style="font-family:;"></span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">n3</span><span style="font-family:;">⋯⋯</span><span style="font-family:;"></span><span style="font-family:;">C</span><span style="font-family:;">nm</span><span style="font-size:10.5pt;font-family:;"></span><span style="font-family:宋体;"> </span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</div>

# 输出文件


<p style="text-align:left;text-indent:21.0pt;" align="left">
	对于每组数据，如果无法得到宝藏则输出：
</p>
<div align="center">
	<table style="border:none;" border="1" cellpadding="0" cellspacing="0">
		<tbody>
			<tr>
				<td style="border:solid windowtext 1.0pt;" valign="top" width="449">
					<p style="text-align:left;" align="left">
						<span>No</span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</div>
<p style="text-align:left;text-indent:21.0pt;" align="left">
	否则按如下格式输出S表示最少的移动次数：
</p>
<div align="center">
	<table style="border:none;" border="1" cellpadding="0" cellspacing="0">
		<tbody>
			<tr>
				<td style="border:solid windowtext 1.0pt;" valign="top" width="449">
					<p style="text-align:left;" align="left">
						<span>S</span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
</div>
<h2 style="text-align:left;" align="left">
	【输入样例】
</h2>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	3
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	4 7
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	<a name="OLE_LINK9"></a><a name="OLE_LINK8"></a>.O..##.
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	.#.....
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	.#.####
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	.#...X.
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	4 5
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	O....
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	.....
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	.....
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	....X
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	1 3
</p>
<p style="margin-left:21.0pt;text-align:left;" align="left">
	O#X
</p>
<h2 style="text-align:left;" align="left">
	【输出样例】
</h2>
<p style="text-align:left;text-indent:21.0pt;" align="left">
	4
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
	2
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
	No
</p>
<h2 style="text-align:left;" align="left">
	【样例解释】
</h2>
<p style="text-align:left;" align="left">
	   下面是第一个样例的一种最优方案：
</p>
<p style="margin-left:39.0pt;text-align:left;text-indent:-18.0pt;" align="left">
	1.
向东移动一步。
</p>
<p style="margin-left:39.0pt;text-align:left;text-indent:-18.0pt;" align="left">
	2.
向北发射蓝色传送门。
</p>
<p style="margin-left:39.0pt;text-align:left;text-indent:-18.0pt;" align="left">
	3.
向南发射黄色传送门。
</p>
<p style="margin-left:39.0pt;text-align:left;text-indent:-18.0pt;" align="left">
	4.
向北移动一步。（进入蓝色传送门并发生传送）
</p>
<p style="margin-left:39.0pt;text-align:left;text-indent:-18.0pt;" align="left">
	5.
向东发射蓝色传送门。（旧的蓝色传送门消失）
</p>
<p style="margin-left:39.0pt;text-align:left;text-indent:-18.0pt;" align="left">
	6.
向南移动一步。（进入黄色传送门并发生传送）
</p>
<p style="margin-left:39.0pt;text-align:left;text-indent:-18.0pt;" align="left">
	7.
向西移动一步。（得到宝藏）
</p>
<h2 style="text-align:left;" align="left">
	【数据规模】
</h2>
<p style="text-align:left;" align="left">
	<span>       </span>两个测试点
</p>
<table style="border:none;" border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="54">
				<p style="text-align:left;" align="left">
					<span style="font-family:宋体;">编号</span><span style="font-family:;"></span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="57">
				<p style="text-align:left;" align="left">
					<span style="font-family:宋体;">分值</span><span style="font-family:;"></span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="57">
				<p style="text-align:left;" align="left">
					<span style="font-family:宋体;">时限</span><span style="font-family:;"></span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="400">
				<p style="text-align:left;" align="left">
					<span style="font-family:宋体;">描述</span><span style="font-family:;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="54">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">1</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="57">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">40</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="57">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">10s</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="400">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">T&lt;=200   N,M&lt;=8</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="54">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">2</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="57">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">60</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="57">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">1s</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="400">
				<p style="text-align:left;" align="left">
					<span style="font-family:;">T&lt;=100  
  N,M&lt;=50</span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<br/>
</p>
