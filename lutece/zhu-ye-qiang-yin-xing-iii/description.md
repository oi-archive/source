
# Content

若干年后,柱爷再次来到了喵哈哈城,准备再干一票!!

这一次,喵哈哈城早已不是之前的样子,喵哈哈城里有$N$个银行,用$N-1$条双向马路相连,银行的编号为$0,1,2,......,N-1$,任意的两个银行间接或直接都能相互到达.

第i条马路会有一个权值$d{_i}$,表示柱爷经过这条马路需要花费的精力值,从马路的任意一端出发,这个权值保持不变.

柱爷决定从这些银行中抢一部分银行,只要柱爷的精力值**非负**,柱爷就能洗劫所在点的银行;当然因为柱爷抢银行抢的特别熟练,所以柱爷抢银行是不需要花费精力值的.

柱爷到达了$0$号银行,在洗劫$0$号前,柱爷突然想知道一个问题:如果我有x点精力值,我能抢劫几个银行呢.

你能帮柱爷解决这抢劫的小小问题吗？

# Standard Input

第一行,一个正整数:$N$表示银行个数.

接下去$N-1$行,每行一个$3$个非负整数:$u,v,d$表示第$u$号银行和第$v$号银行之间有一条需要花费$d$精力值的马路.

接下去一个非负整数:$q$表示柱爷共有$q$个问题.

接下去有q行,每行有一个非负整数:$x$表示这次柱爷设想自己有x的精力值.

 数据保证:

* $1 \leq N \leq 500$

* $1\leq d{_i}\leq 10000$
* $0 \leq u，v < N$
* $1 \leq q \leq 1000$ 
* $0 \leq x \leq 5000000$

# Standard Output

输出一共有$q$行,每行一个整数:$ans$表示柱爷第$q$次设想时最多可以抢的银行数目.

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
1 0 5
2 0 3
4
2
3
10
11</td><td>1
2
2
3</td></tr></table>


# Constraints



# Note



# Source


