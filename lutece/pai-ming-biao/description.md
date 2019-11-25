
# Content

暑假前集训已经过了一半了，我们将会把当前排名公布出来。但是此刻秋实大哥却心急火燎，因为他不慎把排名删除了。

一共有$n$个人参加排名，每个人都有一个名次，没有哪两个人的名次是相同的。现在秋实大哥掌握的一些情报，比如$A_i$的名次要先于$B_i$。（编号从1开始）

你能帮秋实大哥恢复出排名表吗？

# Standard Input

第一行一个数字 $T\ (T \leq 10)$，表示测试数据组数

每组测试数据，第一行两个数 $n（1 \leq n \leq 200）$和 $m（0 \leq m \leq 40000）$，接下来$m$行，每行两个数$a$和$b$（$1 \leq a,b \leq N$），表示$a$的名次要先于$b$

# Standard Output

对于每组测试数据，输出一行，从$1$号到$n$号每个人的名次。

如果有多个解，让编号为1的人的名次尽量小，然后让编号为2的人的名次尽量小，然后让编号为3的人的名次尽量小......

如果没有解，输出$-1$

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
<tr><td>5
4 0
4 1
1 1
4 2
1 2
2 1
4 1
2 1
4 1
3 2</td><td>1 2 3 4
-1
-1
2 1 3 4
1 3 2 4</td></tr></table>


# Constraints



# Note

注意可能会有重边

# Source


