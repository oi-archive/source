
# Content

为了考察三澄美琴的聪明程度，中堂系给三澄美琴出了一道题
![](/source/lutece/zhong-tang-xi-de-kun-nan-ren-wu/img/aHR0cDovLzViMDk4OGU1OTUyMjUuY2RuLnNvaHVjcy5jb20vaW1hZ2VzLzIwMTgwMzI5LzA2MWIyNmI3YjgwMDQ5ZTY5MzE0MmEzZTIyZjdkM2Q4LmpwZWc=.jpeg)

给定 $n$ 个整数 $A_i$ ，可以确定 $n$ 个 $B_i=\sum_{j=i}^n A_j$。

$$
f(i,j)=
\begin{cases}
0 & (i,j)=(1,1)\\
\min\{f(i-1,j+1),f(i,\lceil \frac{j}{2}\rceil)+B_i\} & i,j\in [1,n],(i,j)\neq (1,1)\\
10^{11037} & otherwise
\end{cases}
$$

求 $f(n,1)$。

# Standard Input

共有$t$组数据
$t\le 100,n\le 1e5$, 总共的$N\le 10^5,1\le A_i\le 10^4$, $A_{i+1} \le A_i$

# Standard Output

输出$f(n,1)$

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
3
1 1 1
5
28 26 25 24 1
10
996 901 413 331 259 241 226 209 139 49</td><td>5
233
11037</td></tr></table>


# Constraints



# Note



# Source


