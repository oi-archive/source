# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2439/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjQzOS9wcm9ibGVtc19pbWFnZXMvMjgzNi8xNTYzXzEuanBn.jpg"><br></p> 

 
 # 输入格式 
<p>
<img border="0" src="/source/joyoi/tyvj-2439/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjQzOS9wcm9ibGVtc19pbWFnZXMvMjgzNi8xNTYzXzIuanBn.jpg"><br></p> 

 
 # 输出格式 
<p>
对于每组数据，若最小的不协调度不超过1018，则第一行一个数表示不协调度若最小的不协调度超过1018，则输出"Too hard to arrange"(不包含引号)。每个输出后面加"--------------------"</p> 

 
 # 提示 
<p>
总共10个测试点，数据范围满足：<br> <br>测试点	T	N	L	P<br>1	≤10	≤18	≤100	≤5<br>2	≤10	≤2000	≤60000	≤10<br>3	≤10	≤2000	≤60000	≤10<br>4	≤5	≤100000	≤200	≤10<br>5	≤5	≤100000	≤200	≤10<br>6	≤5	≤100000	≤3000000	2<br>7	≤5	≤100000	≤3000000	2<br>8	≤5	≤100000	≤3000000	≤10<br>9	≤5	≤100000	≤3000000	≤10<br>10	≤5	≤100000	≤3000000	≤10<br>所有测试点中均满足句子长度不超过30。<br><br></p> 
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
<tr><td>4
4 9 3
brysj,
hhrhl.
yqqlm,
gsycl.
4 9 2
brysj,
hhrhl.
yqqlm,
gsycl.
1 1005 6
poet
1 1004 6
poet
</td><td>108
--------------------
32
--------------------
Too hard to arrange
--------------------
1000000000000000000
--------------------

【样例说明】
前两组输入数据中每行的实际长度均为6，后两组输入数据每行的实际长度均为4。一个排版方案中每行相邻两个句子之间的空格也算在这行的长度中(可参见样例中第二组数据)。每行末尾没有空格。</td></tr></table>
