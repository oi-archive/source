
# Content

出题人`Acnext`又要背锅了，他必须出一道大家都会做的简单题，如果有人做不出来他就得背锅，聪明的你能解决这道简单题让他避免背锅吗：

给出一个长$n$的数列，以及$n$个操作，操作涉及区间加法，单点查询

# Standard Input

第一行输入一个数字$n ,(1 \le n \le 50000)$

第二行输入$n$个正整数，第$i$个数字为$a_i,(1 \le a_i \le 10^9)$，空格隔开

接下来输入$n$行询问，每行输入四个数字$\mathrm{opt},l,r,c$

若$\mathrm{opt}=0$,表示将$[l,r]$的数字都加$c$

若$opt=1$,表示询问$a_r$的值（忽略$l,c$)

# Standard Output

对于每次询问，输出一行代表答案

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
1 0 1 0
0 1 2 2
1 0 2 0</td><td>2
5</td></tr></table>


# Constraints



# Note

分块做法有加分哦

# Source


