# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;2010年7月底，LH、SQ、ZHY、XX和NK前往烟台参加NOI2010。<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;到烟台是要坐火车的，因此出发前大家决定到火车站集中。我们可以把他们所在城市的地图看成是一个直角坐标系，火车站在原点。集中前大家在各自的家里，并且所有人的家都在第一象限内（不会有两个人家的位置相同）。每个人都有一个交通工具，比如XX的单车，NK的汽车等，且这些交通工具可以被看做是完全相同的。每个人有两个途径到火车站：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)&nbsp;乘坐自己的交通工具到火车站；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)&nbsp;先乘坐自己的工具到别人家，然后和别人一起乘坐交通工具到火车站。<BR>&nbsp;&nbsp;&nbsp;&nbsp;比如以下两个方案都是合法的：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)&nbsp;XX和SQ分别乘车到LH家，然后三个人一起乘车到火车站；而ZHY和NK分别乘坐他们的私家车到火车站；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)&nbsp;XX先乘车到SQ家，然后两人一起乘车到LH家，接着三人一起乘车到ZHY家，然后四人一起乘车到NK家，最后五人一起乘车到火车站。<BR>&nbsp;&nbsp;&nbsp;&nbsp;车子是要耗油的，因此他们希望耗油量最少。已知每辆车子无论载多少人，耗油量都是每千米1升。给定每个人家的坐标（任意两个人家的距离即是它们的几何距离，单位千米），求出把所有人集中到火车站（即原点）的最小耗油量。<BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行是一个正整数N，表示总人数（即家的个数）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2到N+1行，每行两个正整数xi,yi表示每个人家的横纵坐标。<BR><BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出共一行，一个数，表示把所有人集中到火车站的最小耗油量(保留两位小数)。<BR> 

 
 # 提示 
样例解释：<BR>(1,2)和(2,1)都乘车到(1,1),然后三人一起乘车到(0,0)。耗油量为dis[(1,2),(1,1)]+dis[(2,1),(1,1)]+dis[(1,1),(0,0)]≈3.41。<BR><BR>数据范围：<BR>对于20%的数据，&nbsp;所有人的家在一条过原点的直线上;<BR>对于50%的数据，&nbsp;1&lt;=N&lt;=10；<BR>对于100%的数据，1&lt;=N&lt;=1000，1&lt;=xi,yi&lt;=100。<BR><BR> 
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
<tr><td>3
1 1
2 1
1 2

</td><td>3.41

</td></tr></table>
