# 

 
 # 题目描述 
给出一个n*m&nbsp;像素的位图文件，每个像素点要么是黑色，要么是白色，但至少有一个点<BR>是白色。第i&nbsp;行、第j&nbsp;列的像素点记为pixel&nbsp;(i,j)。两个像素点p1=(i1,j1)&nbsp;和p2=(i2,j2)&nbsp;之<BR>间的距离定义为:<BR>d(p1,p2)=|i1-i2|+|j1-j2|.<BR>我们的任务是从bit.in&nbsp;中读取位图的信息；<BR>对于每一个像素点，计算与它最近的白点之间的距离； 

 
 # 输入格式 
输入的第一行为两个整数n,m，其中1&lt;=n,m&lt;=200，之间用一个空格隔开。下面的n&nbsp;行，每行为一个长度为m&nbsp;的01&nbsp;字符串，依次逐行描述了位图的信息，1&nbsp;表示白点，0&nbsp;表示<BR>黑点。 

 
 # 输出格式 
输出共n&nbsp;行，每行m&nbsp;个整数，同一行中的相邻两数之间严格要求用一个空格隔开。一个数，即x和y的和<BR> 

 
 # 提示 
所有数据满足1&lt;=n,m&lt;=200 
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
0001
0011
0110

</td><td>3 2 1 0
2 1 0 0
1 0 0 1
</td></tr></table>
