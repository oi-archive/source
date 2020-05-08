
# Content

![](/source/lutece/ai-wo-he-ni-jiang-zhe-gua-chao-xiu-xian-de/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDIwLzA0LzA5L0c0MUVzMS5qcGc=.jpg) ![](/source/lutece/ai-wo-he-ni-jiang-zhe-gua-chao-xiu-xian-de/img/aHR0cHM6Ly9zMS5heDF4LmNvbS8yMDIwLzA0LzA5L0c0MVJGVS5qcGc=.jpg)

涅普迪努很喜欢吃瓜。在她生日那天，妹妹涅普姬雅给她买了 $n$ 个西瓜，第 $i$ 个西瓜的美味度为 $a_i$。由于涅普迪努本质是一台~~复读~~游戏机，她会将这些美味度转化成二进制存进她的大脑里。现在她要在脑内进行下面两种操作：

 1. 将编号在 $[l,r]$ 内的西瓜都添加上美味度为 $c$ 的配料，使得这些西瓜的美味度变成 $a_i\oplus c$（其中 $\oplus$ 表示异或）；
 2. 如果涅普迪努在编号为 $[l,r]$ 内的西瓜中任意选择一些西瓜同时吃掉，那么她将获得的幸福度为这些西瓜的美味度的异或和（如果她一个西瓜都不选，那么获得的幸福度为 $0$）。那么对于所有选择，她能够获得多少种不同的幸福度？（注：该操作不会让西瓜真正被吃掉）。

由于这是她 $T$ 岁生日，涅普姬雅给她买了 $T$ 批西瓜。然而收到的西瓜太多，涅普迪努的脑容量也有限，无法在脑内快速进行这些操作。涅普姬雅请求你来帮助她实现这些操作。

# Standard Input

第一行一个整数 $T$ ($1\leq T\leq 2\times 10^5$)，表示一共有 $T$ 批西瓜（即 $T$ 组数据）；

接下来对于每一批西瓜，第一行输入两个整数 $n,m$ ($1\leq n\leq 2\times 10^5,1\leq m \leq 4\times 10^4$)，表示这一批西瓜有 $n$ 个，并且涅普迪努要在脑内进行 $m$ 次操作；

接下来一行输入 $n$ 个整数，第 $i$ 个整数为 $a_i$ ($0\leq a_i\leq10^9$)，表示这一批西瓜中第 $i$ 个西瓜的美味度；

接下来 $m$ 行，每一行首先输入一个整数 $op$ ($op\in\{1,2\}$)：

 1. 若 $op=1$，那么输入 $l,r,c$ ($1\leq l\leq r\leq n,0\leq c\leq 10^9$)，表示第一个操作；
 2. 若 $op=2$，那么输入 $l,r$，表示第二个操作。

数据保证 $\sum n \leq 2\times 10^5,\sum m\leq 4\times 10^4$

# Standard Output

对于每一个操作 2，输出一行一个整数，表示答案。

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
<tr><td>1
5 4
1 5 3 4 2
2 2 3
1 4 5 3
1 1 3 2
2 1 5</td><td>4
8</td></tr></table>


# Constraints



# Note

对于样例的解释：

首先询问 $[2,3]$，这里面能够获得幸福度为 $0,3,5,6$，一共 $4$ 种幸福度，其中幸福度 $6$ 是通过 $3\oplus 5$ 得到；

之后将 $[4,5]$ 内的西瓜的美味度全部异或上 $3$，此时这些西瓜的美味度为 $1, 5, 3, 7, 1$；

之后将 $[1,3]$ 内的西瓜的美味度全部异或上 $2$，此时这些西瓜的美味度为 $3, 7, 1, 7, 1$；

之后询问所有西瓜，能够得到的幸福度为 $0,1,2,3,4,5,6,7$，一共 $8$ 种幸福度，其中幸福度 $5$ 是通过 $3\oplus 7\oplus 1$ 获得。

# Source


