
# Content

<center>![字母加法等式](/source/lutece/ji-ye-yu-jia-fa-deng-shi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA4NS8yMDE1MDQyNTEyMTAxMTg0MzQzLnBuZw==.png)</center>

一天，上小学的妹妹跑过来问基爷一道字母加法等式，基爷不假思索的便给出了一组可行解。

聪明的你发现，一个字母等式可能有多种不同解，于是你想编个程序计算一下

# Standard Input

输入包含多组数据。

每组数据第一行一个整数`n`，表示有n个字符串 `3 ≤ n ≤ 10`

接下来n行，每行有1个最多只含10个大写字母的字符串，前 n - 1 行的字符串表示加数，第 n 行的字符串表示和

每个样例最多只有10个互不相同的大写字母，每个字母表示 `0 - 9` 中的一个数，`相同字母表示相同的数，不同字母表示不同的数`

# Standard Output

对于每组数据输出一个整数，表示不同的可行解的数量。

对于两个可行解，只要有一个字母表示不同的数字，我们就认为这两个可行解不同

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
TAI
SHEN
LA
ACER
3
SEND
MORE
MONEY</td><td>76
1</td></tr></table>


# Constraints



# Note

1.  `如果各个字符串长度不等，右对齐后再运算`
2.  `每个字符串最左边的字母表示的数字不能为0`
3.   `不保证最后一个字符串的长度大于等于前面的表示加数的字符串长度`

# Source


