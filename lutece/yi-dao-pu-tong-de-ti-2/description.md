
# Content

给出一个长为 $n$ 的数列 $a_1\ldots a_n$，以及 $n$ 个操作，操作涉及区间开方，区间求和。

# Standard Input

第一行输入一个数字 $n (1 \le n \le 50000)$。

第二行输入 $n$ 个非负整数，第$ i $个数字为 $a_i,(0 \le a_i \le 10^9)$，以空格隔开。

接下来输入 $n$ 行询问，每行输入四个数字 $opt,l,r,c$，以空格隔开。

若 $opt=0$，表示将位于$[l,r]$ 的之间的数字都开方。对于区间中每个 $ai(l≤i≤r),ai\rightarrow⌊√ai⌋$

若 $opt=1$，表示询问位于$[l,r]$ 的所有数字的和。

# Standard Output

对于每次询问，输出一z行一个数字表示答案。

保证所有数据在`int`范围内

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
<tr><td>4
1 2 2 3
0 1 3 1
1 1 4 4
0 1 2 2
1 1 2 4</td><td>6
2</td></tr></table>


# Constraints



# Note



# Source


