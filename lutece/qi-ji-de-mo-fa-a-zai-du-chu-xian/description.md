
# Content

#### 想对你说的话，如山似海。——$Asahina\,Mirai$    

![](https://www.asahi.co.jp/precure/maho/img/top/logo.png "")    

决战之后，魔法界和无魔法界分离，为了和$Riko$再次相见，$Mirai$必须用经受考验，唤醒奇迹的魔法。    
那考验就是——出现了$n$个非负整数$a\_1,a\_2,{\ldots},a\_n$，  
对于$m$次询问，第$j$次询问给定一个正整数$x\_j$，   
输出$max\\{a\_1\;XOR\;x\_j\;\;,\;\;a\_2\;XOR\;x\_j\;\;,\;\;{\ldots}\;\;,\;\;a\_n\;XOR\;x\_j\\}$。

$XOR$运算：$0\;XOR\;1\,=\;1\;$，$\;1\;XOR\;0\,=\;1\;$，$\;0\;XOR\;0\;=\;0\;$，$\;1\;XOR\;1\;=\;0\;$。    
按位$XOR$运算：对两个数的二进制位依次进行$XOR$运算。    
还对$XOR$运算不懂的请去百度或谷歌一下：异或。

# Standard Input

输入的第一行为一个正整数$n$，    
接下来一行是$n$个非负整数$a\_1,a\_2,{\ldots},a\_n$。    
接下来为一个正整数$m$，    
接下来一行，为$m$个非负整数$x\_1,x\_2,...,x\_m$。

# Standard Output

输出$m$行，每行$1$个值，表示所求答案。

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
<tr><td>5
1 8 0 5 14
5
7 14 10 4 2
</td><td>15
15
15
12
12
</td></tr></table>


# Constraints



# Note

$1{\leq}n{\leq}100000$，    
$1{\leq}m{\leq}100000$，    
$0{\leq}a\_i{\leq}2147483647$，    
$0{\leq}x\_i{\leq}2147483647$

# Source


