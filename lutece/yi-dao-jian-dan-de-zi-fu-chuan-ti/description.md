
# Content

对于一个字符串，我们可以写出这个字符串的所有非空前缀。例如“abab”，非空前缀有：“a”,“ab”，“aba”，“abab”。对于每一个前缀，我们可以计算出他在原字符串中出现的次数。所以我们可以看到，“a”在原字符串中出现了2次；  
“ab”在原字符串中出现了2次；“aba”出现了1次；“abab”出现了一次。  
现在，要求您计算出给定的字符串的所有非空前缀出现的次数之和。对于“abab”，答案就是2+2+1+1=6。  
由于答案可能非常大，所以要求输出答案对10007取模的值。

# Standard Input

输入由2行组成；  
第一行输入一个正整数n（n<=1000000），代表字符串的长度；  
第二行输入一个长度为n的字符串，只由小写字母构成。

# Standard Output

输出由一行组成；  
输出一个整数，代表给定的字符串的所有非空前缀出现的次数之和对10007取模的值。

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
abab
</td><td>6</td></tr></table>


# Constraints



# Note



# Source


