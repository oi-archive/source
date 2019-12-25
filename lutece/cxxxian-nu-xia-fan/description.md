
# Content

一年一度的仙女下凡送温暖活动开始了，参加仙女节的一共有k个仙女，cxx是最小的k仙女，她们下凡的铁路网上一共有$n$个车站和$m$趟单向列车，每趟列车会花费一定的时间，车站编号从$1$到$n$，她们统一从$s$号车站出发，目标是$t$号车站。她们是按照年龄从大到小的顺序来下凡的。并且希望下凡路上的时间尽量的短，但是她们每一个人都是特立独行的，都不希望自己的路径和之前的某个仙女**完全**一样（例如：年龄最大的仙女走的就是图中从$s$到$t$的时间最短的路径），现在cxx想知道她下凡时需要花费多少时间？

# Standard Input

第一行三个正整数$n(1\leq n \leq1500),m(1\leq m \leq80000),k(1\leq k \leq1500)$表示车站和列车的数量，以及仙女的数量

第二行两个正整数$s,t$表示仙女下凡的开始车站和结束车站编号$(1\leq s,t\leq n)$ 保证$s$与$t$不同

接下来m行每行三个整数$u,v,w$表示从车站$u$到车站$v$有一趟花费时间为$w$的单向列车（任意时间仙女都可以花费$w$的时间从$u$到$v$）$(1\leq u,v\leq ,0\leq w\leq10^9)$
如果cxx无法找到自己中意的路径，请输出-1

# Standard Output

一行一个整数表示cxx下凡时花费的时间

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
<tr><td>3 6 3
1 3
1 3 1
1 2 2
2 3 3
2 3 4
1 3 8
1 3 10</td><td>6</td></tr></table>


# Constraints



# Note



# Source


