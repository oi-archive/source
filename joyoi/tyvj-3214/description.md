# 

 
 # 题目描述 
<p>
分配问题（job.cpp/c/pas）<br><br>【问题描述】<br><br>　　有n件工作要分配给n个人做。第i 个人做第j 件工作产生的效益为Cij 。试设计一个将n件工作分配给n个人做的分配方案，使产生的总效益最大。<br><br>【编程任务】<br><br>　　对于给定的n件工作和n个人，计算最优分配方案和最差分配方案。<br></p> 

 
 # 输入格式 
<p>
由文件job.in提供输入数据。<br>　　文件的第1 行有1 个正整数n，表示有n件工作要分配给n 个人做。接下来的n 行中，每行有n 个整数Cij ，1≤i≤n，1≤j≤n，表示第i 个人做第j件工作产生的效益为Ｃij 。</p> 

 
 # 输出格式 
<p>
程序运行结束时，将计算出的最小总效益和最大总效益输出到文件job.out中。</p> 
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
<tr><td>5
2 2 2 1 2
2 3 1 2 4
2 0 1 1 1
2 3 4 3 3
3 2 1 2 1</td><td>5
14</td></tr></table>
