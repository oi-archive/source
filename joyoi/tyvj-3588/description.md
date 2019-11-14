# 

 
 # 题目描述 
<p>
N个点用M条有向边连接，每条边标有一个小写字母。<br><br>对于一个长度为D的顶点序列，回答每对相邻顶点Si到Si+1的最短回文路径。<br><br>如果没有，输出-1。<br><br>如果有，输出最短长度以及这个字符串。<br><br> <br><br></p> 

 
 # 输入格式 
<p>
第一行正整数N和M  ( 2 ≤ N ≤ 400 ,  1 ≤ M ≤ 60,000 )<br>接下来M行描述边的起点，终点，字母。<br>接下来D表示询问序列长度 ( 2 ≤ D ≤ 100 )<br>再接下来D个1到N的整数<br><br></p> 

 
 # 输出格式 
<p>
对于D-1对相邻点，按要求输出一行。<br>如果没合法方案，输出-1。<br><br>如果有合法，输出最短长度以及这个字符串。空格隔开。<br><br></p> 
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
<tr><td>6 7

1 2 a

1 3 x

1 4 b

2 6 l

3 5 y

4 5 z

6 5 a

3

1 5 3
</td><td>
3 ala

-1
</td></tr></table>
