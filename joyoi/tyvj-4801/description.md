# 

 
 # 题目背景 
<p><span style="color: rgb(0, 0, 0); font-family: 宋体; font-size: 16px;">&nbsp;&nbsp;上决╇ф成功地阻止了大魔王的复活，于是西南科技大学信息工程学院又举行了一年一度的院赛。为了让比赛能够顺利进行，上决╇ф让FM负责布置比赛的其中一个赛场，上决╇ф告诉FM报名参加的只有男生队和女生队两种，赛场可以看做一个N行M列的矩阵教室，每个位置上只可以容纳一支队伍（男生队或者女生队）。</span></p> 

 
 # 题目描述 
<p><span style="color: rgb(0, 0, 0); font-family: 宋体; font-size: 16px;">现在上决╇ф通过某种交易得到了一些数据，这些数据包含的信息如下：</span></p>

<p style="margin: 5px 0px; color: rgb(0, 0, 0); font-family: sans-serif; font-size: 16px;"><span style="font-family: 宋体;">&nbsp;&nbsp;1.</span><span style="font-family: 宋体;">如果第i行第j列的位置坐的是男生队，那么此队将得到A[i][j]的战斗力。</span></p>

<p style="margin: 5px 0px; color: rgb(0, 0, 0); font-family: sans-serif; font-size: 16px;"><span style="font-family: 宋体;">&nbsp;&nbsp;2.</span><span style="font-family: 宋体;">如果第i行第j列的位置坐的是女生队，那么此队将得到B[i][j]的战斗力。</span></p>

<p style="margin: 5px 0px; color: rgb(0, 0, 0); font-family: sans-serif; font-size: 16px;"><span style="font-family: 宋体;">&nbsp;&nbsp;3.</span><span style="font-family: 宋体;">如果第i行第j列的队伍在相邻的位置中有x支异性队伍（相邻指的是两位置有公共边，显然x&lt;=4），那么这个队伍能得到x*c[i][j]的额外战斗力加成。</span></p>

<p style="margin: 5px 0px; color: rgb(0, 0, 0); font-family: sans-serif; font-size: 16px;"><span style="font-family: 宋体;">&nbsp;&nbsp;4.</span><span style="font-family: 宋体;">如果第i行第j列的队伍在相邻的位置中有x支同性队伍（相邻指的是两位置有公共边，显然x&lt;=4），那么这个队伍的战斗力会减少x*d[i][j]。&nbsp;&nbsp;</span><span style="font-family: 宋体; text-indent: 28px;">上决╇ф要求FM根据上面的数据，合理安排每个位置，使得整个赛场所有队伍的战斗力总和最大。上决╇ф只是让FM布置这一个赛场，所以保证了男生队和女生队数量足够。你能帮FM求出最大的战斗力总和吗？</span></p> 

 
 # 输入格式 
<p>输入第一行为两个整数N和M，代表赛场大小。<br />
接下来依次给出四个N行M列的矩阵A[i][j]&nbsp;,&nbsp;B[i][j]&nbsp;,&nbsp;C[i][j]&nbsp;,&nbsp;D[i][j]&nbsp;,&nbsp;四个矩阵的数据代表的意义就是题面所述。<br />
其中：1&nbsp;&lt;=&nbsp;N&nbsp;,&nbsp;M&nbsp;&lt;=&nbsp;100&nbsp;,&nbsp;0&nbsp;&lt;=&nbsp;A[i][j]&nbsp;,&nbsp;B[i][j]&nbsp;,&nbsp;C[i][j]&nbsp;,&nbsp;D[i][j]&nbsp;&lt;=&nbsp;500。</p> 

 
 # 输出格式 
<p>输出一个整数，代表最大的战斗力。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3 3
1 2 3
4 5 6
7 8 9

9 8 7
6 5 4
3 2 1

1 2 1
2 1 2
1 2 1

1 1 1
1 1 1
1 1 1
</td><td>81
</td></tr></table>
