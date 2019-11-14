# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;在一个有N个地级市的X省，政府为了城市开发建设，决定先修路，后造房子，以吸引外来人员。<BR>&nbsp;&nbsp;&nbsp;&nbsp;一开始每个城市中有b[i]个住户，而在两个城市u,v之间建路需要的代价就是R乘以u,v两个城市的住户数目之和。建路的目标是使得所有城市相互之间都可达。<BR>&nbsp;&nbsp;&nbsp;&nbsp;建完路之后，就要造房子了，由于X省的房产商仅此一家，所以只能一户一户的造房子。不过政府有权利任意安排建造的顺序，在城市i建造一个房子的代价是，h[i]乘以城市i当前住户数目同城市i周边城市(即通过道路直接相连的)的当前住户数目之和。由于现在房子炙手可热，所以每造好一户，就立刻有用户入住。<BR>&nbsp;&nbsp;&nbsp;&nbsp;政府决定最后的目标是每个城市a[i]个住户。作为政府部门的财务主管，请你计算出最少需要花费多少钱，才可以完成上述要求。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行一个整数N，表示有N个城市；<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来一行有N个整数，描述b数组，也就是每个城市一开始的住户数；<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来一行有N个整数，描述a数组，也就是每个城市最终的住户数；<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来一行有N个整数，描述h数组，表示建房费用；<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来有一个N*N的矩阵，矩阵的第i行第j个元素表示，原来i城市和j城市是否有路相连。Y表示有，N表示没有。<BR>&nbsp;&nbsp;&nbsp;&nbsp;最后一行一个整数R，表示建路的费用。 

 
 # 输出格式 
一个数，表示最小费用。(答案可能需要用64位整数才能表示)<BR> 

 
 # 提示 
数据规模<BR>N≤50<BR>注意事项：<BR>数据保证b[i]≤a[i]&nbsp;≤100000；	h[i]，R≤100000；对于N*N的矩阵是对称的。<BR>空间限制<BR>64MB清北学堂杯2011NovTyvj月赛(提高组难度)第一题 
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
<tr><td>4
1 1 1 1
1 3 1 2
8 5 3 2
NYNN
YNYN
NYNY
NNYN
100000</td><td>39</td></tr></table>
