# 

 
 # 题目描述 
<p>
给出一个宽为W,高为H的矩形 。<br>在它上面有两种点，black及white.<br>每个点都有自己的辐射范围。对于其它的点如果它受到白点的辐射多于黑色的，则为<br>白点，反之亦然，如果相同的话则中立.<br>现给出白点及黑色的坐标及各自的辐射范围，问最后白色点一共有多少个，黑色点共有多少个 。</p> 

 
 # 输入格式 
<p>
第一行给出W和H，左下角坐标为(0,0), 右上角为(W-1,H-1).<br>1 ≤ W,H ≤1 000 000 000<br>第二行给出数字N，代表有多少个点。0 ≤ N ≤ 3 000<br>接下来N行，每行先给出点的属性，再给出坐标，再给出辐射范围，其在[0, 500 000 000)<br></p> 

 
 # 输出格式 
<p>
两个数，分别代表白色点有多少个，黑色点有多少个 。</p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2300/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjMwMC9wcm9ibGVtc19pbWFnZXMvMjY3MC8xMzkyLmpwZw==.jpg"></p> 
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
<tr><td>10 10
3
W 3 6 3
B 6 4 2
W 3 3 2</td><td>30 9</td></tr></table>
