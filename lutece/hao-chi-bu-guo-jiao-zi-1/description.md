
# Content

给出两个长度分别为$n$和$m$的数组$a$和$b$，问有多少个起点$k(0 \le k \le n-m)$满足

$a[k]+b[0]=a[k+1]+b[1]=⋯=a[k+m-1]+b[m-1]$

# Standard Input

第一行两个正整数$n,m(1 \le n \le 10^5,2 \le m \le 10^5 )$；

第二行n个整数，为数组$a(-3\times10^9 \le a[i] \le 3\times10^9)$；

第三行m个整数，为数组$b(-3\times10^9 \le b[i] \le 3\times10^9)$。

# Standard Output

第一行输出一个整数表示有多少个起点满足条件；
	第二行按从小到大的顺序输出这些起点，用空格隔开。

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
<tr><td>5 3
1 4 6 9 11
5 2 0
</td><td>2
0 2
</td></tr></table>


# Constraints



# Note

好吃不过饺子，可爱不过老子。

 ——LargeDumpling

# Source


