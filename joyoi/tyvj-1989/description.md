# 

 
 # 题目背景 
神犇xhm给kAc出了一题，kAc必然不会了所以向你请教<br><br><br> 

 
 # 题目描述 
给定N个整数A[1..N]<br>现在有两种操作：<br>	操作1：选择一个连续子序列[l,&nbsp;r]，把他们的数值全部增加T<br>	操作2：询问数列中某个元素A[i]的值是多少。<br>为了降低难度，我们先执行Q1次操作1，再执行Q2次操作2。这个任务你能完成吗？<br><br><br> 

 
 # 输入格式 
第一行三个正整数&nbsp;N,&nbsp;Q1,&nbsp;Q2<br>第二行N个整数，描述数列A<br>接下来Q1行每行3个整数l,&nbsp;r,&nbsp;T,如题目所述。保证l&nbsp;&lt;=&nbsp;r。<br>接下来Q2行每行一个p,表示询问A[p]的值。<br><br> 

 
 # 输出格式 
对于每个询问,输出一行一个整数,表示答案。<br><br> 

 
 # 提示 
1&lt;=N,&nbsp;Q1,&nbsp;Q2&lt;=100000&nbsp;保证A中的数值的绝对值随时&lt;=10^16<br><br><br> 
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
<tr><td>3 2 3
1 1 1
1 3 1
2 3 2
1
2
3

</td><td>2
4
4

</td></tr></table>
