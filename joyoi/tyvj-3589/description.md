# 

 
 # 题目描述 
<p>
</p> 

 
 # 输入格式 
<p>
第一行正整数 n m p k    (1 ≤ n ≤ 200, 0 ≤ m ≤ 3 000, 1 ≤ p ≤ 13, 0 ≤ k ≤ n).<br><br>分别表示点数，边数，剑/怪物的型号数，铁匠数。<br><br> <br><br>接下来k行描述铁匠，格式如下：<br><br>所在点编号w，所能锻造的剑种类数q，升序给出q个1到p的不同的整数表示型号。<br><br> <br><br>接下来m行描述边：<br><br>连接的顶点 x y，通过需要的时间t，路上的怪物数s，s个单调上升的1到p整数表示怪物型号。<br><br> </p> 

 
 # 输出格式 
<p>
<br><br>第一行输出最少时间。如果无法到达 输出-1<br></p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-3589/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzU4OS9wcm9ibGVtc19pbWFnZXMvMjQzOC8xMTM5LmpwZw==.jpg"> </p> 
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
<tr><td>6 7

1 2 a

1 3 x

1 4 b

2 6 l

3 5 y

4 5 z

6 5 a

3

1 5 3
</td><td>3 ala

-1</td></tr></table>
