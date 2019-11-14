
# Content

给定三个大小为$N$的整型数组$A1,A2,A3$，和三个整数$B1,B2,B3$。

接下来依次做$N$次操作：对于第$i$次操作$(i=1,2,..,N)$，选择一个数$j$($j=1,2,3$)，令$Bj$加上$Aj[i]$。

问是否存在一种操作序列，使得最后$B1 = B2 = B3 = 0$。

# Standard Input

第一行四个数$N(1<=N<=25),B1,B2,B3$。

接下来N行，每行三个整数，表示$A1[i],A2[i]$和$A3[i]$。

保证$|A1[i]|,|A2[i]|,|A3[i]|,|B1|,|B2|,|B3|<=10^9$。

# Standard Output

如果存在符合要求的方案，输出$"YES"$；否则输出$"NO"$。

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
<tr><td>3 1 1 1
-1 2 3
1 -1 2
2 3 -1</td><td>YES</td></tr><tr><td>3 1 1 1
1 1 1
1 1 1
1 1 1</td><td>NO</td></tr></table>


# Constraints



# Note



# Source


