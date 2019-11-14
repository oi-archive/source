
# Content

酱神要去一棵树上旅行。

酱神制定了一个旅行计划，他要按顺序去$m$个树上的结点，$a1,a2,a3,...,am$。

酱神有一辆车，树上的每一条边既可以开车通过，也可以走过去，两种方法需要不同的时间。如果选择走路，酱神需要先把车停在结点上，在他下一次要开车的时候，必须先回到停车的结点取车。

酱神和他的爱车一开始都在$a1$结点上，酱神要依次访问完这$m$个结点最少需要多少时间。

# Standard Input

第一行两个数$n, m$。

$1=<n, m<=5000$

接下来$n-1$行，每行$4$个数，$u, v, walk, drive$。表示结点$u$和结点$v$之间有一条走路耗时为$walk$，开车耗时为$drive$的边。

$1=<u, v<=n$

$1=<walk, drive<={10}^{9}$

最后输入$m$个数，$a1,a2,a3,...,am$， 酱神要按顺序访问的结点。

$1=<ai<=n$

# Standard Output

输出一个数，酱神的最小耗时。

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
<tr><td>2 2
1 2 3 100
1 2
</td><td>3
</td></tr><tr><td>4 4
1 2 1 20
3 2 100 1
2 4 1 100
1 2 3 4
</td><td>23
</td></tr></table>


# Constraints



# Note



# Source


