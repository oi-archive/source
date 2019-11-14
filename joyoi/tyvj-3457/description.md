# 

 
 # 题目描述 
<p>
数学家旅游（GOLYGON.pas/c/cpp）<br><br>    有一个城市的道路由规则的方砖组成。有一位数学家来到参观，他可沿方砖的边沿行走，有四种方法：n(0,1), s(0,-1), e(1,0), w(-1,0)，但他是一个很怪的数学家，他会走一段时间休息一会儿，然后继续走。他有几个很特别的特性：<br>    不喜欢休息后走的方向和休息前一样；<br>    第一次休息前走一步，休息后走的距离比休息前的距离长一步；<br>    不喜欢重复走同一个地方；<br>    要走回出发点。<br>    我们称他的路线是一个golygon，我们可以将出发的地点记为（0，0），城市有几个地点正在施工，是不可以通行的。为了这位奇怪的科学家可以旅游得开心，我们决定帮他设计旅游的方案，找出城市中有多少个他希望的golygon。<br></p> 

 
 # 输入格式 
<p>
    输入文件golygon.in第一行是golygon最大边的大小（不大于20），第二行是施工地点的个数（不大小50），以下的每行有两个数字，表示施工的地点的坐标。</p> 

 
 # 输出格式 
<p>
输出文件golygon.out：每一个golygon的走法，每个占一行，最后输出golygon的个数。</p> 

 
 # 提示 
<p>
按“北南东西”的顺序遍历各个方向，才能在多解的情况下与标准输出完全一致。</p> 
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
<tr><td>8
2
-2  0
6  -2
</td><td>wsenenws
Found 1 golygon(s).</td></tr></table>
