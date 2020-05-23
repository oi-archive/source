
# Content

AK 了一场比赛后的糖哥非常的无聊，于是他随意地画出一棵含 $n$ 个节点的树，然后他想把 $0$ 到 $n-2$ 这 $n-1$ 个非负整数一一分配给每条边作为边权。

怎么分配呢？糖哥随意地定义了一个函数 $f(x,y)$，表示从点 $x$ 到点 $y$ 的最短路径上所有的边权中，最小的没有出现的非负整数。然后他又随意地定义了 $\displaystyle S=\sum_{1\le x<y\le n}f(x,y)$。糖哥想找出一种分配方案，使得 $S$ 最大。

无敌的糖哥当然知道怎么分配，但是他想考考你 $S$ 的最大值是多少。

# Standard Input

第一行为一个整数 $n$ ($2 \le n \le 3000$)，表示树的节点数。

接下来 $n-1$ 行，每行两个整数 $u$ 和 $v$ ($1 \le u,v \le n$)，表示点 $u$ 与 点 $v$ 间存在一条边。

输入数据保证是一颗树。

# Standard Output

输出 $S$ 的最大值。

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
1 2
2 3</td><td>3</td></tr><tr><td>5
1 2
1 3
1 4
3 5</td><td>10</td></tr></table>


# Constraints



# Note

对于第 1 个样例，下面这种分配方式能使 $S$ 最大：

![1.png](/source/lutece/wu-liao-de-tang-ge/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDQvMTEvNnk3RDV6d2ROR2gzaVBjLnBuZw==.png)

在这种方式下，$f(1,2)=0$，$f(1,3)=2$，$f(2,3)=1$。因此 $S=0+2+1=3$。

对于第 2 个样例，下面这种分配方式能使 $S$ 最大：

![2.png](/source/lutece/wu-liao-de-tang-ge/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDQvMTEvUzlZRWFNR0RUbTJWa0FOLnBuZw==.png)

在这种方式下，$f(1,3)=1$，$f(1,5)=2$，$f(2,3)=1$，$f(2,5)=2$，$f(3,4)=1$，$f(4,5)=3$，其他点对 $f(u,v)=0$。因此 $S=1+2+1+2+1+3=10$。

# Source


