# 

 
 # 题目描述 
你需要完成一个配对的任务，且得到的权值最大。规定一个AB序列的权值和是：<br>	<img src="/source/joyoi/tyvj-2013/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjAxMy9wcm9ibGVtaW1nL3AyMDEzLmpwZw==.jpg" border=0 align=middle><br>	这里给出一个简单的例子，例如A序列&nbsp;{1，2，3，4}，B序列&nbsp;{5，6，7，8}，则这个配对的权值是1*6+3*8=30。注意，你不能改变A序列和B序列内数的位置，更不能交换A、B序列。<br>	现在给出A序列和B序列，为了使得到权值更大，允许删除若干个数（当然也可以不删除），这里只允许同时删除A序列、B序列的第K个数，且要保证最后AB序列的长度为偶数。按照上例来举例，删除A、B序列第1、4的数，得到的两个序列是A{2,3}，B{6,7}，删除后序列权值是2*7=14。<br>	你的任务就是使得AB序列的权值最大。<br><br><br> 

 
 # 输入格式 
输入文件第1行为一个数N（保证是偶数），表示原始A,B序列的长度。<br>	第2行N个数，表示序列A[i]。<br>	第3行N个数，表示序列B[i]。<br><br><br> 

 
 # 输出格式 
输出文件仅一行，表示最大的AB序列权值。<br><br> 

 
 # 提示 
【样例解释】<br>原始的AB序列权值为5，如果我们删除A、B序列的第1,4个，得到的权值是100，并且是所有方案中最大的。<br><br>【数据规模和约定】<br>对于20%的数据，N&lt;=10<br>对于50%的数据，N&lt;=5000<br>对于100%的数据，N&lt;=100000，0&lt;=A[i],b[i]&lt;=1,000,000，最终答案不会超过2^63<br><br><br>Admin(zhqc)&nbsp;Tyvj三周年邀请赛&nbsp;第三题<br><br> 
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
1 10 5 1
0 0 10 1


</td><td>100


</td></tr></table>
