
# Content

ZH，24 岁，是学生。他觉得很多东西都是臭的，比如某些数字。他认为，对于某个数，把它看作一个不含前导零的字符串，如果这个字符串中包含长度大于等于 $2$ 的回文子串，那么这个数就是臭数。比如 $114514$ 中包含回文子串 $11$，因此它是臭数。又比如 $1919810$ 包含回文子串 $191$、$919$，因此它也是臭数。注意，一个字符串本身也是它的子串，比如 $616$ 也是臭数。

ZH 想知道，从 $L$ 到 $R$ 的所有整数中有多少个臭数，包含端点。由于答案可能很大，只需要输出答案对 $1000000007$ 取模的余数。

# Standard Input

输入两个整数 $L$ 和 $R$ ($0 \le L \le R < 10^{1000}$)。

# Standard Output

输出从 $L$ 到 $R$ 的所有整数中有多少个臭数，答案对 $1000000007$ 取模。

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
<tr><td>1 100</td><td>10</td></tr><tr><td>100 1000</td><td>253</td></tr></table>


# Constraints



# Note

子串的定义：串中若干个连续的字符组成的串。

回文串的定义：反转以后和原串相同的串。

# Source


