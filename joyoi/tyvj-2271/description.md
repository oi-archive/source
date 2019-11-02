# 

 
 # 题目描述 
<p>
给出一个平行四边形的长与高.<br>给出入口与出口,对于四边形的每条边都有一种Color,非黑即白.<br>你要找出一条路径,走过的边黑白交替,且长度最短</p> 

 
 # 输入格式 
<p>
第一行给出平行四边形的长与高.且值在[1,500]<br>第二行给出入口,出口坐标.<br>下面的字符矩阵代表这个平行四边形每条边的Color</p> 

 
 # 输出格式 
<p>
输出路径的最少长度</p> 

 
 # 提示 
<p>
对于第一个数据:<br>(0, 0) -> (1, 0) -> (0, 1) -> (1, 1) -> (1, 0) ->(2, 0) -> (2, 1)<br><br><img border="0" src="/source/joyoi/tyvj-2271/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI3MS9wcm9ibGVtc19pbWFnZXMvMjY0MC8xMzUzLmpwZw==.jpg"><br><br>对于第二个数据:<br>(0, 2) -> (1, 2) -> (1, 1) -> (2, 1) -> (2, 0) -><br>(3, 0) -> (3, 1) -> (3, 2) -> (4, 1) -> (3, 1) -><br>(3, 0) -> (2, 0) -> (2, 1) -> (1, 1) -> (1, 2) -><br>(1, 3) -> (2, 3) -> (2, 4) -> (3, 4) -> (3, 3) -><br>(4, 3) -> (4, 2) -> (5, 2)</p> 
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
<tr><td>inupt 1
2 1
0 0 2 1
bb
nwwnw
bn

input 2
5 4
0 2 5 2
nnbnn
nnnwwbwnnnn
nbbbn
nnwbwwbwwnn
bwwww
nnbwbbwwbnn
nwwwn
nnnnbwbbnnn
nnwnn</td><td>output 1
6

output 2
22</td></tr></table>
