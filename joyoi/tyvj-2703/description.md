# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2703/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjcwMy9wcm9ibGVtc19pbWFnZXMvMzIwMS8xOTM3LmpwZw==.jpg"> </p> 

 
 # 输入格式 
<p>
第一行为N、M，其中 表示顶点的数目， 表示边的数目。顶点的编号为1、2、3、……、N-1、N。接下来的M行，每行三个整数Ui，Vi，Wi，表示顶点Ui与Vi之间有一条边，其权值为Wi。所有的边在输入中会且仅会出现一次。再接着N-1行，每行两个整数Xi、Yi，表示顶点Xi与Yi之间的边是T的一条边。<br><br></p> 

 
 # 输出格式 
<p>
输出最小权值</p> 
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
<tr><td>6 9
1 2 2
1 3 2
2 3 3
3 4 3
1 5 1
2 6 3
4 5 4
4 6 7
5 6 6
1 3
2 3
3 4
4 5
4 6

</td><td>8

【样例说明】
	
边(4,6)的权由7修改为3，代价为4
边(1,2)的权由2修改为3，代价为1
边(1,5)的权由1修改为4，代价为3
所以总代价为4+1+3=8

修改方案不唯一。</td></tr></table>
