# 

 
 # 题目描述 
<p>
我们的郭嘉大大在曹操这过得逍遥自在，但是有一天曹操给了他一个任务，在建邺城内有N（<=1000）个袁绍的奸细，将他们从1到N进行编号，同时他们之间存在一种传递关系，即若C[i，j]=1，则奸细i能将消息直接传递给奸细j。

 
 # 输入格式 
<p>
文件的第一行为N，第二行至第N+1行为N*N的矩阵（若第I行第J列为1，则奸细I能将消息直接传递给奸细J，若第I行第J列为0，则奸细I不能将消息直接传递给奸细J）。</p> 

 
 # 输出格式 
<p>
输出文件只有一行：即我们的郭嘉大大首先至少要传递的奸细个数。</p> 
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
<tr><td>8
0 0 1 0 0 0 0 0  
1 0 0 1 0 0 0 0  
0 1 0 1 1 0 0 0  
0 0 0 0 0 1 0 0  
0 0 0 1 0 0 0 0  
0 0 0 1 0 0 0 0  
0 0 0 1 0 0 0 1 
0 0 0 0 0 0 1 0 </td><td>2</td></tr></table>