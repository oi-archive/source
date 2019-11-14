# 

 
 # 题目描述 
<p>
最多30000x30000的黑白棋盘，不超过1000个连通分量。<br>每个连通分量的大小不超过1000。<br>分别统计各种大小连通分量的数量。<br></p> 

 
 # 输入格式 
<p>
第一行给出棋盘大小.<br>下面有n行，用来描述每一行有哪些格子是黑色的</p> 

 
 # 输出格式 
<p>
输出连通块的大小，及有多少块 </p> 

 
 # 提示 
<p>
下图对应样例 <br><img border="0" src="/source/joyoi/tyvj-2277/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI3Ny9wcm9ibGVtc19pbWFnZXMvMjY0NC8xMzY0LmpwZw==.jpg"></p> 
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
<tr><td>12
2-4,7,9;
1,4,11-12;
1,4,10,12;
1,4-8,10-12;
1,8;
1,3-6,8,10-12;
1,3,5-6,8,11;
1,8,10-12;
1-8;
;
2;
2-4,7-10,12;</td><td>29 1
7 3
4 2
1 3</td></tr></table>
