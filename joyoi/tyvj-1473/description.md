# 

 
 # 题目描述 
&nbsp;校门外有很多树，有苹果树，香蕉树，有会扔石头的，有可以吃掉补充体力的……<BR>如今学校决定在某个时刻在某一段种上一种树，保证任一时刻不会出现两段相同种类的树，现有两个操作：<BR>K=1，读入l,r表示在l~r之间种上的一种树<BR>K=2，读入l,r表示询问l~r之间能见到多少种树<BR>（l,r&gt;0）<BR> 

 
 # 输入格式 
第一行n,m表示道路总长为n，共有m个操作<BR>接下来m行为m个操作<BR> 

 
 # 输出格式 
对于每个k=2输出一个答案 

 
 # 提示 
范围：20%的数据保证，n,m&lt;=100<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;60%的数据保证，n&nbsp;&lt;=1000,m&lt;=50000<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100%的数据保证，n,m&lt;=50000<BR>注意：树是可以重叠的，比如1号位置上可以种多种树 
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
<tr><td>5 4
1 1 3
2 2 5
1 2 4
2 3 5
</td><td>1
2
</td></tr></table>
