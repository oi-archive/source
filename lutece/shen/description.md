
# Content

oy获得了神给予的字符串密码
字符串密码是一个长度为k的倍数的字符串s.
神知道oy精通分块,所以密码的解密也和分块息息相关
神要求oy将字符串按照从左到右的顺序每k个分为一块,每块当中的元素可以按照自己的意愿重新排列,但是块与块之间的先后顺序应该保持不变.
解密的答案即是重排后字符串中包含的最小段数,其中每一段是一连串相同的字母.
例如:"baabcbaca"在k=3时分为3块 baa bcb aca,那么显然重排为aabbbccaa为最优,此时有四段.

# Standard Input

输入包含多组测试数据,第一行为一个整数T,代表总测试数.
以下2T行每行包含一个整数k与字符串s,含义如上述.
保证串长是k的整数倍
***
update:字符串由小写字母组成

# Standard Output

对于每组数据,输出重排后的最小段数

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
<tr><td>1
3
baabcbaca</td><td>4</td></tr></table>


# Constraints

$1 \leq T \leq 100$

$1 \leq k,|s| \leq 1000$

# Note



# Source


