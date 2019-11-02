# 

 
 # 题目描述 
<p>
运输问题（trans.pas/c/cpp）<br><br>【问题描述】<br><br>　　W 公司有m个仓库和n 个零售商店。第i 个仓库有i a 个单位的货物；第j 个零售商店需要bj个单位的货物。货物供需平衡，即<img src="/source/joyoi/tyvj-3213/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxMy9wcm9ibGVtc19pbWFnZXMvMTYyMC9wMS5naWY=.gif"></img>。从第i 个仓库运送每单位货物到第j 个零售商店的费用为ij c 。试设计一个将仓库中所有货物运送到零售商店的运输方案，使总运输费用最少。<br><br>【编程任务】<br><br>　　对于给定的m 个仓库和n 个零售商店间运送货物的费用，计算最优运输方案和最差运输方案。</p> 

 
 # 输入格式 
<p>
由文件trans.in提供输入数据。<br>　　文件的第1行有2 个正整数m和n，分别表示仓库数和零售商店数。接下来的一行中有m个正整数i a ，1≤i≤m，表示第i个仓库有i a 个单位的货物。再接下来的一行中有n个正整数j b ，1≤j≤n，表示第j个零售商店需要j b 个单位的货物。接下来的m行，每行有n个整数，表示从第i 个仓库运送每单位货物到第j个零售商店的费用Ｃij 。<br><br></p> 

 
 # 输出格式 
<p>
程序运行结束时，将计算出的最少运输费用和最多运输费用输出到文件trans.out中。<br></p> 
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
<tr><td>2 3
220 280
170 120 210
77 39 105
150 186 122</td><td>48500
69140</td></tr></table>
