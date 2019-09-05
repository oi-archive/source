# 题目描述


<p>
	【问题描述】
</p>
<p>
	   Fj设计了一个绘画程序，这个绘画程序就是在N(行)*N（列）的方格里，给某些区域各自染上不同的颜色。颜色一共有K种，标号分别是1..K.默认颜色为白色(标号为1)。
</p>
<p>
	   N*N的方格里的最左上的那个格子的编号为(0,0)。某个格子的编号为(x,y)，这里x是所在格子的行标，y是所在列的列标。
</p>
<p>
	   Fj的绘画程序有三种不同的命令
</p>
<p>
	1）  PAINT命令：PAINTc x1y1x2y2 给(x1,y1)到(x2,y2)这个矩形染上C的颜色，不过这种染色不是在整个区域全部染上颜色C，而是在x1,y1染上染上颜色c，其余交错染色，如下图所示，这是一个染上红色的矩形。（注意：白色是底色，并不是染上白色，也就是说白色区域并没有染色。）
</p>
<p>
	<img src="/images/upload/image/20120705/20120705105240_83394.jpg" alt=""/> 
</p>
<p>
	2）  SAVE命令：SAVE      将当前棋盘的颜色存储起来。
</p>
<p>
	3）  LOAD命令：LOAD x     将棋盘的颜色变为第x次存储的状态。
</p>
<p>
	最初棋盘是纯白色(颜色代码是1),给出M条命令，每条命令肯定是以上三种命令中的一种，问M条命令后，棋盘的状态。
</p>
<p>
	【输入】
</p>
<p>
	第一行三个整数N(1≤N≤1000),K(2≤K≤100000),和M(1 ≤M≤100000)意义如题目所示。
</p>
<p>
	 接下来M行，为M条命令。
</p>
<p>
	【输出】
</p>
<p>
	N行*N列的矩阵，每行中整数用单个空格隔开，表示棋盘的颜色状态。
</p>
<p>
	<br/>
</p>
<p>
	【输入输出样例1】
</p>
<table border="1">
	<tbody>
		<tr>
			<td>
				<p>
					drawing.in
				</p>
			</td>
			<td>
				<p>
					drawing.out
				</p>
			</td>
		</tr>
		<tr>
			<td>
				<p>
					<br/>
				</p>
4 3 2
PAINT 2 0 0 3 3
PAINT 3 0 3 3 3
				<p>
					<br/>
				</p>
			</td>
			<td>
				<p>
					<br/>
				</p>
2 1 2 3
1 2 1 2
2 1 2 3
1 2 1 2
				<p>
					<br/>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<br/>
</p>
<p>
	【输入输出样例2】
</p>
<table border="1">
	<tbody>
		<tr>
			<td>
				<p>
					drawing.in
				</p>
			</td>
			<td>
				<p>
					drawing.out
				</p>
			</td>
		</tr>
		<tr>
			<td>
				<p>
					<br/>
				</p>
3 3 4
PAINT 3 0 0 1 1
SAVE
PAINT 2 1 1 2 2
LOAD 1
				<p>
					<br/>
				</p>
			</td>
			<td>
				<p>
					<br/>
				</p>
3 1 1
1 3 1
1 1 1
				<p>
					<br/>
				</p>
				<p>
					<br/>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	【输入输出样例3】
</p>
<table border="1">
	<tbody>
		<tr>
			<td>
				<p>
					drawing.in
				</p>
			</td>
			<td>
				<p>
					drawing.out
				</p>
			</td>
		</tr>
		<tr>
			<td>
				<p>
					<br/>
				</p>
3 4 7
PAINT 2 0 0 1 1
SAVE
PAINT 3 1 1 2 2
SAVE
PAINT 4 0 2 0 2
LOAD 2
PAINT 4 2 0 2 0
				<p>
					<br/>
				</p>
			</td>
			<td>
				<p>
					<br/>
				</p>
2 1 1
1 3 1
4 1 3
				<p>
					<br/>
				</p>
				<p>
					<br/>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<br/>
</p>
<p>
	【数据范围】
</p>
<p>
	  30%数据保证N&lt;=100 M&lt;=4000
</p>
