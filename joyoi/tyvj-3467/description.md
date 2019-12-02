# 

 
 # 题目描述 
<p>
相邻项序列（T4.pas/c/cpp)<br><br>【问题描述】<br>　　对于一个N*N(≤100)的正整数矩阵M，存在从M[A1，B1] 开始到M[A2，B2]结束的相邻项序列.两个项M[I，J]和M[K，L]相邻的件是指满足如下情况之一：<br>　　(1)I=K+-1和J=L <br>　　(2)I=K和J=L+-1。 <br>　　任务：从文件中输入矩阵M，再读入K(K<=4)组M[A1，B1]和M[A2，B2]的值。对于每一组M[A1，B1]和M[A2，B2]，求一相邻项序列，使得相邻项之差的绝对值之和为最小。<br></p> 

 
 # 输入格式 
<p>
输入文件T4.in<br>第一行一个数值N，接下来N行，每行N个数据，为N*N的矩阵<br>第N+2行为K，表示后面跟着K组数据，<br>接下来K行，每行一组数据，表示A1,B1和A2,B2的值，<br><br></p> 

 
 # 输出格式 
<p>
输出文件T4.out<br>共k组数据，每组数据两行，<br>每组数据第一行表示第i组数据相邻项之差的绝对值之和的最小值<br>第二行第i组数据的相邻项序列<br><br></p> 
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
1 9 6 12
8 7 3 5 
5 9 11 11
7 3 2 6
2
4 1 1 4 
2 2 3 4 </td><td>1 17 
7 5 8 7 9 6 12
2 4
7 9 11 11</td></tr></table>
