# 

 
 # 题目描述 
<p>
消息传递问题（dianji.pas/c/cpp）

 
 # 输入格式 
<p>
　　输入文件dianji.in第一行为N；第二行为N个大于0小于100的整数，表示老师传递信息给学生的相应代价；第三行至第N+2行为N*N的矩阵。（若第I行第J列为1，则学生I能将消息直接传递给学生J；若第I行第J列为0，则学生I不能将消息直接传递给学生J）。(N<100)</p> 

 
 # 输出格式 
<p>
　　输出文件dianji.out第一行为老师首先至少要通知的学生个数；第二行为老师所要付出的最小代价；第三行为首先得到消息的学生的编号，从小到大排列输出。</p> 
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
<tr><td>7
10 8 15 27 20 4 6 
0 0 1 0 0 0 0
1 0 0 0 0 0 0
0 1 0 0 0 1 0
0 0 0 0 1 1 0
0 0 0 1 0 0 1
0 0 0 0 0 0 0
0 0 0 0 0 1 0
</td><td>2
28
2 5</td></tr></table>