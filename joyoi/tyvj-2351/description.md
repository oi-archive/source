# 

 
 # 题目描述 
<p>
<br>有一个M * N的棋盘，有的格子是障碍。现在你要选择一些格子来放置一些士兵，一个格子里最多可以放置一个士兵，障碍格里不能放置士兵。我们称这些士兵占领了整个棋盘当满足第i行至少放置了Li个士兵, 第j列至少放置了Cj个士兵。现在你的任务是要求使用最少个数的士兵来占领整个棋盘。<br></p> 

 
 # 输入格式 
<p>
第一行两个数M, N, K分别表示棋盘的行数，列数以及士兵的个数。<br>第二行有M个数表示Li。<br>第三行有N个数表示Ci。<br>接下来有K行，每行两个数X, Y表示(X, Y)这个格子是障碍。<br></p> 

 
 # 输出格式 
<p>
输出一个数表示最少需要使用的士兵个数。如果无论放置多少个士兵都没有办法占领整个棋盘，输出”JIONG!” (不含引号)<br></p> 
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
<tr><td>4 4 4
1 1 1 1
0 1 0 3
1 4
2 2
3 3
4 3
</td><td>4
数据范围
M, N <= 100, 0 <= K <= M * N</td></tr></table>
