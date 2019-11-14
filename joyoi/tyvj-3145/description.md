# 

 
 # 题目描述 
<p>
　　给定一个m行n列的方格阵，每个方格边长为1。要从方格阵左上方的顶点（0，0）走到右下方的顶点（m，n），中间有若干个格子是障碍物，无法通过。人可以从（x1，y1）走到（x2，y2），当且仅当（x1<=x2）且（y1<=y2）且线段（x1，y1）-（x2，y2）不穿过任意一个障碍方格。求最短路长度。</p> 

 
 # 输入格式 
<p>
　　文件的第一行包括3个用空格分开的正整数m，n。以下是一个邻接矩阵A，1表示表示障碍。</p> 

 
 # 输出格式 
<p>
　　文件只有一行。文件应只一个精确到小数点后面2位小数的实数，表示最短路径的长度。</p> 

 
 # 提示 
<p>
【提示】<br><br>以下是示例数据的一种答案：<br>　　注意：图中红色的部分告诉我们，尽管路线不能穿越障碍方格，但是可以沿着障碍方格行进。<br>　　数据范围：<br>　　　　　　1≤m，n≤80，输入数据无需判错。<br><br><center><img src="/source/joyoi/tyvj-3145/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE0NS9wcm9ibGVtc19pbWFnZXMvMTQzMi8xLmJtcA==.bmp"></img></center>　<br></p> 
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
<tr><td>　　3 　4
　　0 0 1 0
　　0 1 0 0
　　0 0 0 1
</td><td>　5.47</td></tr></table>
