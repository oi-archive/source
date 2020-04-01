# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2432/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjQzMi9wcm9ibGVtc19pbWFnZXMvMjgyNS8xNTUyLmpwZw==.jpg"> </p> 

 
 # 输入格式 
<p>
输入共两行，第一行为一个整数N，N表示物品的个数，1<=N<=100000。第二行为N个用空格隔开的正整数，表示N个物品最初排列的编号。<br></p> 

 
 # 输出格式 
<p>
输出共一行，N个用空格隔开的正整数P1,P2,P3…Pn，（1 < = Pi < = N），Pi表示第i次操作前第i小的物品所在的位置。<br>注意：如果第i次操作前，第i小的物品己经在正确的位置Pi上，我们将区间[Pi,Pi]反转(单个物品)。<br></p> 
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
<tr><td>6
3 4 5 1 6 2

</td><td>4 6 4 5 6 6</td></tr></table>
