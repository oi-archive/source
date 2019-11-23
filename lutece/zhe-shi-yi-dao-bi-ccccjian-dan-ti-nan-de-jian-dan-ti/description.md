
# Content

集训队的CFT大爷精通Python

有一天，CFT大爷跑在vps上的python爬虫程序挂了

CFT大爷经过缜密的推断，发现程序挂了的原因是Python的垃圾回收机制不够优越，导致内存炸了，那些卖vps的奸商强行杀掉了他的爬虫程序

CFT大爷决定再也不用python这门垃圾语言，他要发明一个新的语言CFTthon

CFT大爷的CFTthon是跑在CFT大爷以前写的CFT_OS上的，在CFT_OS中，内存布局是一个n\*m的长方形矩阵，而CFTthon所有的变量，都只占用1\*2大小的小长方形内存空间。

CFT大爷在手写CFTthon的GC系统时，想到了一个问题：给定n,m，要求用CFTthon的变量把整个内存空间完全覆盖，不重合不遗漏，有多少种方法呢？

\*\*\*\* 扯淡题意分割线 \*\*\*\*

给定一个n\*m的矩阵，使用1\*2的小长方形覆盖矩阵，要求完全覆盖的同时不出现重合，也不允许超出边界，问有多少种可能的覆盖方法,方案数对1e9+7取模

2<=n<=1000

3<=m<=5

# Standard Input

整数n,m

# Standard Output

方案数

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
<tr><td>2 4</td><td>5</td></tr></table>


# Constraints



# Note

注意取模

# Source


