# 

 
 # 题目描述 
<p>
Farmer John 获得了几个新的农场！他想要将这些农场连接起来，以便他能够在农场之间穿行。有些农场之间已经有路连接了。<br>N (1 ≤ N ≤ 1,000) 个农场中的每一个（用1..N连续编号） 用平面坐标（ Xi， Yi ）（ 0  ≤  Xi  ≤  1,000,000;  0  ≤  Yi  ≤  1,000,000 ）表示。给定M（ 1  ≤  M  ≤  1,000 ）已经存在的道路。请你帮助Farmer John 决定需要修建的最短道路长度，使得所有农场之间相互连通。<br></p> 

 
 # 输入格式 
<p>
* 第1行：两个用空格分开的整数：N 和 M。<br>* 第2..N+1行：两个用空格分开的整数 Xi 和Yi 。<br>* 第N+2..N+M+2行：两个用空格分开的整数i 和 j，表示在农场i和农场j之间已经有道路连接了。<br></p> 

 
 # 输出格式 
<p>
* 第一行：需要额外修建的道路的最短长度，精确到小数点后两位。注意计算距离的时候要用64位浮点数。</p> 

 
 # 提示 
<p>
在莞中OJ提交通过后，请点击下面链接到POJ再提交一次：<br><a href="http://poj.org/problem?id=3625">http://poj.org/problem?id=3625</a></p> 
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
<tr><td>4 1
1 1
3 1
2 3
4 3
1 4
</td><td>4.00</td></tr></table>
