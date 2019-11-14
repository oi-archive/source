
# Content

一开始你有$n$个字符串$str_i$，每一个字符串有一个权值$a_i$。接下来由$m$个询问，每个询问包含一个字符串$S$和他的权值$k$，对于每一个询问你需要回答

$$\sum_{i=1}^{n}{LCP(str_i,S)*{ka_i}} \bmod 1000000007$$

$LCP(S1,S2)$表示字符串$S1$和字符串$S2$的最长公共前缀的长度。

`不要问我为什么乘一个k，作为审题人我也看不懂，可是乘了就过了`

# Standard Input

第一行一个正整数$n(1 \le n \le 10^5 )$；

接下来n行每行一个字符串$str_i$，和它的权值$a_i (1 \le a_i \le 10^6)$。

然后一行一个正整数$m(1 \le m \le 10^5)$；

接下来$m$行每行一个字符串$S$，和它的权值$k(1 \le k \le10^6 )$

题目保证所有字符串的长度不超过$200$。

# Standard Output

$m$行每行一个整数，为每个询问的回答。

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
larvende 2
larji 3 
largedump 3
2
largedumpling 3
laamofinigxis 3

</td><td>126
48</td></tr></table>


# Constraints



# Note

好吃不过老子，可爱不过饺子。

——DumpeLargling

# Source


