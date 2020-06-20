
# Content

santongding 最近想要学习一些压缩算法。

在他学习已有的算法之前，他想先对一些字符串进行初步研究。为了研究方便，他做出了如下定义：

+ 对于一个的串 $S$ ，其长度为 $|S|$ ，子串 $S[l,r] (1≤l≤r≤|S|)$ 定义为将 $S$ 删去从第一个字符到第 $(l-1)$ 个字符和从第 $(r+1)$ 个字符到最后一个字符后剩下的串。

+ 定义字符串加法 $S_1 + S_2$ 结果为将 $S_2$ 拼接在 $S_1$ 之后形成的串  (例如 "abc" + "defg" = "abcdefg")

+ 定义字符串乘法 $S * n$ ，其中 $S$ 为字符串，$n$ 为正有理数。设 $a$ 为 $n$ 的整数部分，$b$ 为 $n$ 的小数部分，且可以被表示为 $b=c/d$ 。其中，$c$ 和 $d$ 均为非负整数，$c<d$ , 且 $d$ 能整除 $|S|$ 。则该运算的结果为 $\underbrace{S + S + ... + S}_{a个S}+ S[1,|S|*b]$

+ 定义字符串除法：若存在一个正有理数 $n$ ,使 $S_1 * n = S_2$ ，则此时 $S_2/S_1$ 有定义，且结果为 $n$

+ 定义一个串的`santongding压缩系数`: 对一个串 $S$ 的所有子串 $S[l,r] (1≤l≤r≤|S|)$ ，$S/S[l,r]$ 有定义的值中，最大的一个值。

现在，santongding有一个长度为 $n$ 的串 $S$ ，他想知道，对于这个串$S$的所有子串的`santongding压缩系数`，最大的那一个是多少。但santongding现在忙着学习完现有所有压缩算法并发明一个更优秀的算法，于是将这个简单的任务交给了你。

# Standard Input

一行，仅包含小写英文字母的串$S$

# Standard Output

一行，一个既约分数 $a/b$ (a,b互质)，表示串$S$所有子串中最大的`santongding压缩系数`

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
<tr><td>aaaaa</td><td>5/1</td></tr><tr><td>santongdingzipzipzz</td><td>7/3</td></tr><tr><td>abcdefghijklmnopqrstuvwxyz</td><td>1/1</td></tr></table>


# Constraints

1<=|S|<=200000

# Note

第二个样例，选择子串S[12,18] =  "zipzipz"，有最大的`santongding压缩系数`  7/3
("zip" $*$ 7/3 = "zip" + "zip" + "z" = "zipzipz")

# Source


