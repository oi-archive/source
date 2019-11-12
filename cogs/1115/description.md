# 题目描述


<h2 style="text-align:left;" align="left">
	【问题描述】
</h2>
<p>
	<span>       </span><a name="OLE_LINK1"></a><a name="OLE_LINK2"></a>传送门是一个非常有趣的解谜游戏，你位于一个N行M列的迷宫中，这个迷宫有一个宝藏，你希望用尽可能少的移动得到宝藏。
</p>
<p>
	       你可以移动到相邻的四个格子中的空格，或者利用传送门来移动。具体来说，你有一把激光枪，它可以创造两种传送门，黄色传送门和蓝色传送门。每次你可以朝东南西北中的某个方向发射一个能量球，当它击中第一个障碍时会消失并在被击中处形成一个传送门（能量球击中宝藏会直接穿过去）。
</p>
<p>
	       <a name="OLE_LINK4"></a><a name="OLE_LINK3"></a>当且仅当创造了黄色传送门和蓝色传送门之后，你可以进入其中任意一个传送门然后从另一个传送门出来。
</p>
<p>
	       考虑下面的迷宫（灰色格子表障碍，白色格子表空格，红点是你的位置）：
</p>
<p>
	<img src="/cogs/include../../../../../upload/image/20121007/20121007155133_46743.png" alt=""/> 
</p>
<p style="text-indent:21.0pt;">
	假设你向东发射蓝色传送门：
</p>
<p style="text-indent:21.0pt;">
	<img src="/cogs/include../../../../../upload/image/20121007/20121007155133_54285.png" alt=""/> 
</p>
<p>
	       然后向南发射黄色传送门：
</p>
<p>
	<img src="/cogs/include../../../../../upload/image/20121007/20121007155133_44879.png" alt=""/> 
</p>
<p>
	       然后向南移动一步：
</p>
<p>
	<img src="/cogs/include../../../../../upload/image/20121007/20121007155133_39850.png" alt=""/> 
</p>
<p>
	       现在是最有意思的部分，如果你再向南移动一步，那么你会穿过黄色传送门而到达蓝色传送门！
</p>
<p>
	<img src="/cogs/include../../../../../upload/image/20121007/20121007155133_22498.png" alt=""/> 
</p>
<p>
	       当且仅当另一个同色传送门形成时，前一个传送门会消失，譬如你向西边发射一个蓝色传送门，旧的蓝色传送门便会消失：
</p>
<p>
	<img src="/cogs/include../../../../../upload/image/20121007/20121007155133_31613.png" alt=""/> 
</p>
<p>
	       请注意，传送门是位于障碍的某一侧。如果一个障碍的西侧有一个传送门，那么你必须从西边进入这个传送门，否则你就是在撞墙……
</p>
<p>
	       <a name="OLE_LINK6"></a><a name="OLE_LINK5"></a>最后，两个传送门不允许叠在一起，否则它们都会因为能量冲突而消失。
</p>
<p>
	       现在，给你迷宫的地图，你的初始位置，宝藏的位置，请你用尽可能少的移动得到宝藏。注意，发射传送门不计入移动。
</p>
<h2 style="text-align:left;" align="left">
	【输入文件】
</h2>
<p style="text-align:left;" align="left">
	       第一行T表示数据组数，每组数据按如下格式：
</p>
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
<p>
	<span>       </span>C<sub>i,j</sub>用来描述每个格子：
</p>
<p style="margin-left:39.0pt;text-indent:-18.0pt;">
	1.  . 表示一个空格。
</p>
<p style="margin-left:39.0pt;text-indent:-18.0pt;">
	2.  # 表示一个障碍。<span></span> 
</p>
<p style="margin-left:39.0pt;text-indent:-18.0pt;">
	3.  O 表示你的初始位置。<span></span> 
</p>
<p style="margin-left:39.0pt;text-indent:-18.0pt;">
	4.  X 表示宝藏的位置。<span></span> 
</p>
<p style="text-indent:21.0pt;">
	<a name="OLE_LINK7"></a>保证每组数据中O和X(均为大写)出现且只出现一次。你可以认为迷宫之外的部分都是障碍并且可以用来创造传送门。<span></span> 
</p>
<h2 style="text-align:left;" align="left">
	【输出文件】
</h2>
<p style="text-align:left;" align="left">
	       T行，每组数据一行。
</p>
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
