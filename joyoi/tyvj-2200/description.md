# 

 
 # 题目描述 
<p>
矩阵覆盖<br>给定一个N×M的矩阵，矩阵的元素只可能是0,1,2三者之一。现在要求你找到这个矩阵的两个子矩阵，这两个子矩阵可以相交，但是这两个子矩阵必须包含所有的2，不能包含元素1，但是可以包含元素0。在满足以上要求的前提下两个子矩阵并的面积应该尽量小。<br></p> 

 
 # 输入格式 
<p>
输入文件有多组数据。每组数据包含了N,M以及N×M的矩阵。<br></p> 

 
 # 输出格式 
<p>
输出文件包含了数据的答案。对于每组数据你应当输出矩阵并的最小面积，如果无解则输出-1。<br></p> 
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
<tr><td>3 4
1 2 1 0
2 0 2 2
1 2 1 0
3 4
1 2 1 0
2 0 2 2
1 2 1 0
</td><td>
6
6
数据范围：
对于100%的数据，有1<=N,M<=50。
</td></tr></table>
