
# Content

`帆宝`在某天学习RMQ(Range Minimum/Maximum Query)的过程中突然顿悟领悟RMQ的精髓，发明了带修改RMQ，简称帆宝RMQ，复杂度极其优越。`ZinYY`想要学习帆宝RMQ，可是他太弱了，甚至连帆宝RBQ也学不会，所以`帆宝`只能教给他最简单的帆宝RQ(Range Query)

这里定义帆宝RQ为$RQ(x)$，表示数列中最左边$x$与最右边$x$的下标之差的绝对值，当数列中不存在$x$时$RQ(x)=-1$

帆宝讲解完算法并留下一道课堂练习题给`ZinYY`:对于一个长度为$n$的给定数列$a$，有$q$个询问，每种询问有两个类型，类型$1$是将区间$[l,r]$的数都加上$x$,类型$2$是询问$RQ(x)$，并将答案输出

`ZinYY`听完课还是一脸蒙蔽，你能帮他解决这道课堂练习题吗

# Standard Input

第一行包含两个数$n,q$，$1\le n \le 10^5,1\le q \le 5*10^4$

第二行包含$n$个数$a_1,a_2...a_n$，为数列$a$,$1\le a_i \le 10^9$

接下来$q$行，每行有$4$个数或者$2$个数

如果一行以$1$开始，代表类型,输入格式为$1,l,r,x$,$1\le l \le r \le n,0 \le x \le 10^9$

如果一行以$2$开始，代表类型,输入格式为$2,x$,$1\le x \le 10^9$

# Standard Output

对于每个类型$2$,输出$RQ(x)$的值

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
<tr><td>4 3
1 2 3 4
1 1 2 1
1 1 1 1
2 3</td><td>2
</td></tr><tr><td>2 3
1 2
1 2 2 1
2 3
2 4</td><td>0
-1
</td></tr></table>


# Constraints



# Note



# Source


