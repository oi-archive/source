# 题目描述


<p>
	<strong>题目描述</strong>：<strong> </strong><br/>
你试图在直多边形（一个边都以90度或270度相交，而且内部没有洞的多边形）的基础上，一层层地增加新边框，在新的边框多围出来的区域涂上不同的颜色，以取得特殊的装饰效果。增加的边框与上一层增加的边框（第一层边框则是与直多边形的边）的距离都保持一个固定值d，如下图所示：<br/>
<img alt="1" src="http://192.168.1.252/os/times/2011/11gzoi/border_clip_image002.gif" height="113" width="363"/><br/>
图3 装饰效果示例<br/>
在图3左的例子，在直多边形（灰色）的基础上加了两层边框，图3右的例子直多边形形状更复杂些，增加的边框离断成了两部分。注意边框也许离断成若干部分但绝不相交或重叠，即不会发生以下情况：<br/>
<img alt="2" src="http://192.168.1.252/os/times/2011/11gzoi/border_clip_image004.gif" height="106" width="355"/><br/>
图4 不会发生的情况<br/>
你的任务是计算每层增加的边框长度及每层边框多围出来的面积。<br/>
<strong>输入格式</strong>（Border.in）：<br/>
第一行是用空格分隔的三个正整数n,m,d。n是直多边形的边数，m是需要增加边框的层数，n&lt;=100，m&lt;=20，d是边框之间的距离。接下来的若干行，以顺时针方向描述直多边形的n个顶点坐标，每个坐标含空格分隔的两个正整数x和y。第一个顶点坐标满足y坐标最大；如果有多个满足此要求的顶点，我们从当中x坐标最小的开始。<br/>
<strong>输出格式</strong>（Border.out）：<br/>
第一行包含m个整数，按次序输出每层增加的边框长度。<br/>
第二行包含m个整数，按次序输出每层边框多围出来的面积。<br/>
<strong>样例 </strong>
</p>
<table border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top" width="284">
				<br/>
Border.in
			</td>
			<td valign="top" width="284">
				<p>
					Border.out
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="284">
				<p>
					6 2 10<br/>
20 30 100 30 100 0 0 0 0 10 20 10
				</p>
			</td>
			<td valign="top" width="284">
				<p>
					340 420<br/>
3000 3800
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="284">
				<p>
					10 1 7<br/>
20 50 70 50 70 0 0 0 0 30<br/>
20 30 20 10 60 10 60 40 20 40
				</p>
			</td>
			<td valign="top" width="284">
				<p>
					380<br/>
2660
				</p>
			</td>
		</tr>
	</tbody>
</table>
