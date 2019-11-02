# 

 
 # 题目描述 
<p>
给出一个地图.上面有水,有故障点.<br>你要开着一个船走出这个地图.<br>问最少要多少步,否则无解.<br>注意这个船是关于轴对称的.</p> 

 
 # 输入格式 
<p>
第一行给出数字N,代表地图的大小.N在[3,2000]<br>下面N行N列的字符矩阵<br>"."代表水<br>"X"代表故障点<br>"r"代表你的船的一部分.<br>也就是说你的船是由多个相连的r组成的.</p> 

 
 # 输出格式 
<p>
最少的步数离开这个地图.</p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-3569/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzU2OS9wcm9ibGVtc19pbWFnZXMvMjQxMy8xMTE0LmpwZw==.jpg"><br></p> 
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
<tr><td>10
..........
..........
..r.......
.rrrX.....
rrrrr.....
.rrr......
X.r.......
.Xr.......
..........
..........</td><td>
10</td></tr></table>
