# 

 
 # 题目描述 
给定有向图&nbsp;G=(V,E)。设&nbsp;P&nbsp;是&nbsp;G&nbsp;的一个简单路（顶点不相交）的集合。如果&nbsp;V&nbsp;中每个<BR>顶点恰好在&nbsp;P&nbsp;的一条路上，则称&nbsp;P是&nbsp;G&nbsp;的一个路径覆盖。P&nbsp;中路径可以从&nbsp;V&nbsp;的任何一个顶<BR>点开始，长度也是任意的，特别地，可以为0。G&nbsp;的最小路径覆盖是G&nbsp;的所含路径条数最少<BR>的路径覆盖。&nbsp;<BR>设计一个有效算法求一个有向无环图G&nbsp;的最小路径覆盖。&nbsp;<BR>提示：设V={1，2，...&nbsp;，n}，构造网络&nbsp;G1=(V1,E1)如下：&nbsp;<BR>V1&nbsp;=&nbsp;{&nbsp;x0,&nbsp;x1,&nbsp;...,&nbsp;xn}&nbsp;U&nbsp;{&nbsp;y0,&nbsp;y1,&nbsp;...,&nbsp;yn}&nbsp;,<BR>E1&nbsp;=&nbsp;{(x0,xi):i包含于V}&nbsp;U&nbsp;{(yi,y0):i包含于V}&nbsp;U&nbsp;{(xi,yj):(i,j)包含于E}<BR>每条边的容量均为1。求网络G1&nbsp;的（x0,y0&nbsp;）最大流。&nbsp;<BR>′编程任务：&nbsp;<BR>对于给定的给定有向无环图G，编程找出&nbsp;G的一个最小路径覆盖。&nbsp; 

 
 # 输入格式 
第1&nbsp;行有&nbsp;2个正整数&nbsp;n和&nbsp;m。n是给定有向无环图(0&lt;n&lt;=150,0&lt;=m&lt;=n*n)<BR>G&nbsp;的顶点数，&nbsp;m是G&nbsp;的边数。&nbsp;接下来的&nbsp;m行，&nbsp;每行有&nbsp;2&nbsp;个正整数&nbsp;i和&nbsp;j，&nbsp;表示一条有向边(i,j)。&nbsp; 

 
 # 输出格式 
输出最少路径数。 
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
<tr><td>11 12 
1 2 
1 3 
1 4 
2 5 
3 6 
4 7 
5 8 
6 9 
7 10 
8 11 
9 11 
10 11 </td><td>3</td></tr></table>
