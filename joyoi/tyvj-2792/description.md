# 

 
 # 题目描述 
<p>
【问题描述】(level.cpp/c/pas)<br><br>    一条单向的铁路线上，依次有编号为 1, 2, …, n 的 n 个火车站。每个火车站都有一个级别，最低为 1 级。现有若干趟车次在这条线路上行驶，每一趟都满足如下要求：如果这趟车次停靠了火车站 x，则始发站、终点站之间所有级别大于等于火车站 x 的都必须停靠。（注意：起始站和终点站自然也算作事先已知需要停靠的站点）<br>    例如，下表是 5 趟车次的运行情况。其中，前 4 趟车次均满足要求，而第 5 趟车次由于停靠了 3 号火车站（2 级）却未停靠途经的 6 号火车站（亦为 2 级）而不满足要求。<br><center><img src="/source/joyoi/tyvj-2792/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc5Mi9wcm9ibGVtc19pbWFnZXMvMTE2MC9wMS5naWY=.gif"></img></center><br>      现有 m 趟车次的运行情况（全部满足要求），试推算这 n 个火车站至少分为几个不同的级别。<br></p> 

 
 # 输入格式 
<p>
【输入】<br>    输入文件为 level.in。<br>    第一行包含 2 个正整数 n, m，用一个空格隔开。<br>    第 i + 1 行（1 ≤ i ≤ m）中，首先是一个正整数 si（2 ≤ si ≤ n），表示第 i 趟车次有 si 个停靠站；接下来有 si 个正整数，表示所有停靠站的编号，从小到大排列。每两个数之间用一个空格隔开。输入保证所有的车次都满足要求。<br></p> 

 
 # 输出格式 
<p>
【输出】<br>    输出文件为 level.out。<br>    输出只有一行，包含一个正整数，即 n 个火车站最少划分的级别数。<br></p> 

 
 # 提示 
<p>
【数据范围】<br>对于 20%的数据，1 ≤ n, m ≤ 10；<br>对于 50%的数据，1 ≤ n, m ≤ 100；<br>对于 100%的数据，1 ≤ n, m ≤ 1000。<br></p> 
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
92
41356
3356


【输入样例2】
9 3
4 1356
3 356
3 159</td><td>【输出样例1】
2



【输出样例2】
3</td></tr></table>
