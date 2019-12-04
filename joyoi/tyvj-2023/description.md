# 

 
 # 题目背景 
PY最近迷上了一款叫做扫雷的游戏，但是总是踩中雷而死，最后，他找到你，要你帮他求出非地雷的位置。<br> 

 
 # 题目描述 
有一个n*m矩形数阵，其中数字0-8表示此数字周围的雷数，而9表示可能为雷的地方，其中仅有1个未知的地方没有雷，PY想知道，没有雷的地方究竟在哪里。<br> 

 
 # 输入格式 
第1行输入n,m,k。其中n表示矩形的行数,m表示矩形的列数，k表示矩形中共有多少个未知地点。<br>第2到n+1行输入一个n*m的矩形数列（输入的矩形数列保证都为整数）。<br> 

 
 # 输出格式 
输入共1行：如果输入数据满足唯一一个不为地雷的情况下<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输出不为雷的坐标<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;格式为(n1,m1)&nbsp;其中n1为行数&nbsp;m1为列数。<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当输入数据不满足任何地方都不为雷或者有多个地点不为地雷的话，输出Wrong。<br> 

 
 # 提示 
1&nbsp;1&nbsp;1<br>1&nbsp;9&nbsp;1<br>1&nbsp;9&nbsp;1<br>在此矩形数列中，若(2,2)为非地雷坐标时，则(1,2)应为0，与输入数据相悖，所以(2,2)不为输出数据。<br>而(3,2)为非地雷坐标时，则满足输入数据，则输出为(3,2)。<br><br>数据范围：1≤n≤10&nbsp;&nbsp;1≤m≤10<br> 
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
<tr><td>3 3 2
1 1 1
1 9 1
1 9 1
</td><td>(3,2)
</td></tr></table>
