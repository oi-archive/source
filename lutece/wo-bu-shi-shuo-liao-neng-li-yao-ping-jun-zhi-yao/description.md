
# Content

转生异世界时，栗原海里请求神赐予她平均值的能力，导演组故意找了一个不会计算平均数的神，神很自然地给出了最大值与最小值和的一半的结果——在数学上这显然是错误的，但是剧情就变得很有意思了。

形式化地，若有一由 $n$ 个数组成的有限数列 $\{x_n\}$，则这列数的平均值应为 $\bar x=\frac{1}{n}\sum_{i=1}^n x_i$。栗源海里显然知道平均数应该怎么计算，于是她在思考如果利用真正的平均值定义的话情况会是怎样的。

异世界共有 $n$ 个生物，分别编号为 $1\ldots n$。神会以均匀随机的方式选择一个区间 $[l,r]\ (l\le r\le n,l,r\in \mathbb{N}_+)$，并取编号在区间内的所有生物的能力平均值作为栗原海里的能力值。栗原海里想知道，如果用**数学上**的平均值定义的话，自己的能力值有多大的概率小于等于给定值 $k$。

# Standard Input

第一行一个正整数和一个非负整数 $n,k$，表示异世界生物数和给定值 $k$。

第二行 $n$ 个非负整数 $a_i$，第 $i$ 个数表示第 $i$ 个生物的能力值。

# Standard Output

输出一个分数，形如 `p/q` 且 $\gcd(p,q)=1$，表示这个概率。

这里定义 $\gcd(a,0)=|a|\ (a\neq 0)$。

UPD：$\gcd(a,b)$ 指 $a$ 与 $b$ 的[最大公因数](https://baike.baidu.com/item/%E6%9C%80%E5%A4%A7%E5%85%AC%E7%BA%A6%E6%95%B0/869308?fromtitle=%E6%9C%80%E5%A4%A7%E5%85%AC%E5%9B%A0%E6%95%B0&fromid=869104&fr=aladdin)。

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
<tr><td>6 2
1 1 4 5 1 4</td><td>5/21</td></tr><tr><td>7 200000
911245 140662 1025171 682290 163112 84458 20993</td><td>1/4</td></tr></table>


# Constraints

$1\le n\le 2\times 10^5,0\le k,a_i\le 10^9$

# Note

对于第一个样例，满足条件的 $[l,r]$ 区间有 $[1,1],[1,2],[1,3],[2,2],[5,5]$ 五个，因此概率为 $\frac{5}{21}$。

# Source


