
# Content

给你一个字符串$s$，然后再给你$n$个询问，第$i$个询问给你一个数字$k$和一个字符串$m$

这个询问的答案是$t$的最小长度，其中$t$是$s$的子串，且$t$中必须出现$k$个$m$

# Standard Input

第一行一个字符串$S$

第二行数字$Q$，代表询问次数

后面每一行一个$k$和$m$，代表依次询问

数据保证所有字母均为小写字母

$(1 \leq \left | s \right | \leq 10^{5})$

$(1 \leq Q \leq 10^5)$

$(1 \leq k_i \leq |s|)$

所有询问长度加起来小于$100000$

**保证所有字符串不相同**

# Standard Output

$Q$行，每行代表一个询问的答案

无解请输出$-1$

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
<tr><td>aaaaa
5
3 a
3 aa
2 aaa
3 aaaa
1 aaaaa</td><td>3
4
4
-1
5</td></tr><tr><td>abbb
7
4 b
1 ab
3 bb
1 abb
2 bbb
1 a
2 abbb</td><td>-1
2
-1
3
-1
1
-1</td></tr></table>


# Constraints



# Note



# Source


