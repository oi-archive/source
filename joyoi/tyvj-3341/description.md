# 

 
 # 题目描述 
<p>
Platforme（platforme.pas\c\cpp）<br><br>【题目描述】<br>　　为了进行一种游戏，现决定搭造一些平板，而各个平板的地址已经选定。基于最普遍的认识，没有任何支持物的平板不可能漂浮在空中。说的更精确些，任意一平板的两端必需有支柱或者它在另一块平板上。<br>　　你会得到各个平板在坐标系中的坐标（如左下图）。每一块平板的坐标都是由它的高度（与地板间的垂直距离）和它的水平方位（开始和结束）决定的。每个支柱都距它支撑的平板的边缘半个单位（如右下图）。<br>　　算出支持所有平板的支柱的总长度。<br><br><center><img src="/source/joyoi/tyvj-3341/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM0MS9wcm9ibGVtc19pbWFnZXMvMjExNi8xLmpwZw==.jpg"></img></center><br></p> 

 
 # 输入格式 
<p>
　　输入文件Platforme.in第一行包括1个整数N，1 ≤ N ≤ 100，即平板的总数。<br>　　接下来的N行每行都是一块平板的坐标，是相应的Y，X1和 X2。即高度和水平的边缘坐标。所有的数都是不大于10000的正整数且满足X2 > X1+1（也可这样理解，每一块平板的长度至少为2）。<br>　　输入保证任意两块平板间没有重叠部分。<br></p> 

 
 # 输出格式 
<p>
　　输出文件Platforme.out包含要撑起所有平板所需的支柱的总长度。</p> 
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
<tr><td>【输入样例1】
3
1 5 10
3 1 5
5 3 7

【输入样例2】
5
50 50 90
40 40 80
30 30 70
20 20 60
10 10 50

</td><td>【输出样例1】
14

【输出样例2】
200</td></tr></table>
