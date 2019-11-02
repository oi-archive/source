# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2186/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjE4Ni9wcm9ibGVtc19pbWFnZXMvMjUzNC8xMjQwXzEuanBn.jpg"><br><img border="0" src="/source/joyoi/tyvj-2186/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjE4Ni9wcm9ibGVtc19pbWFnZXMvMjUzNC8xMjQwXzIuanBn.jpg"><br><br></p> 

 
 # 输入格式 
<p>
<img border="0" src="/source/joyoi/tyvj-2186/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjE4Ni9wcm9ibGVtc19pbWFnZXMvMjUzNC8xMjQwXzMuanBn.jpg"><br></p> 

 
 # 输出格式 
<p>
对于每一个QUERY操作，输出其相应的答案。<br><br></p> 
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
<tr><td>4 4
1 1 2 1
1 1 1 1
1 1 1 4
QUERY 1 1
INSERT 1 1
QUERY 1 1
DELETE 1
QUERY 1 1
REVERSE 4 1
QUERY 1 1

</td><td>
2
3
2
1

【数据约定】
本题共有10组输入数据，以下给出各组输入数据的具体范围：
Case	1	2	3	4	5	6	7	8	9	10
N	10	100	1000	10000	100000	100000	500000	1000000	1000000	1000000
M	10	100	1000	10000	100000	100000	500000	1000000	1000000	1000000
S1	2	10	100	1000	10000	40000	10000	10000	100000	100000
S2	2	10	100	1000	10000	40000	10000	10000	100000	100000
S3	2	5	10	100	1000	1000	1000	1000	10000	10000
S4	2	5	10	100	1000	1000	1000	1000	10000	10000
TL	1s	1s	1s	1s	1s	3s	3s	5s	10s	10s
</td></tr></table>
