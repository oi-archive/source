
# Content

给出$N$个数，初始值全为$0$，有以下三种操作：

1.将第$x$个数增加$y$.

2.将第$x$个数变成$y$.

3.求第$x$个数到第$y$个数的和。

# Standard Input

第一行一个整数$N(1<=N<=100000)$，代表数的个数。

第二行一个整数$Q(1<=Q<=100000)$，代表询问的个数。

接下来$Q$行，每行第一个整数$op$.

如果$op=1$,输入$x,y$,表示将第$x$个数增加$y(1<=x<=N,1<=y<=10000)$.

如果$op=2$,输入$x,y$,表示将第$x$个数变成$y(1<=x<=N,1<=y<=10000)$.

如果$op=3$,输入$x,y$,表示求第$x$个数到第$y$个数的和$(1<=x<=y<=N)$。

# Standard Output

对于每次$3$号操作，一行输出答案。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>3
5
1 1 1
3 1 3
1 2 4
2 1 2
3 1 2</td><td>1
6</td></tr></table>


# Constraints



# Note



# Source


