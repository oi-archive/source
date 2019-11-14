# 

 
 # 题目描述 
对于完全图G,若有且仅有一棵最小生成树为T，则称完全图G是树T的扩展出的。&nbsp;<BR>给你一棵树T,找出T能扩展出的边权和最小的完全图G。 

 
 # 输入格式 
第一行&nbsp;N&nbsp;表示树T的点数。&nbsp;&nbsp;<BR>接下来N-1行&nbsp;Si&nbsp;Ti&nbsp;Di&nbsp;描述一条边（Si,Ti）权值为&nbsp;Di。&nbsp;&nbsp;<BR>保证输入数据构成一棵树。 

 
 # 输出格式 
一个数，表示最小的图G的边权和。 

 
 # 提示 
添加D(2,3)=2,D(3,4)=3,D(2,4)=3即可。<BR><BR>对于20%的数据&nbsp;N&lt;=10&nbsp;<BR>对于50%的数据&nbsp;N&lt;=1000&nbsp;<BR>对于100%的数据&nbsp;&nbsp;N&lt;=100000&nbsp;1&lt;=Di&lt;=100000&nbsp; 
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
1 2 1  
1 3 1  
1 4 2 </td><td>12</td></tr></table>
