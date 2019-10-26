
# Content

给出两个仅包含小写字符的字符串 A 和 B ，求：对于 A 中的每个回文子串，B 中和该子串相同的子串个数的总和。

如 ababa 和 babab 有 16 个，见 hint 。

# Standard Input

只有一组测试数据，两行字符串。

A 和 B 的长度均小于$200000$

# Standard Output

输出 AB 串中相同的回文子串个数的总和。

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
<tr><td>ababa
babab</td><td>16</td></tr></table>


# Constraints



# Note

A 串中有回文字符串 a b a b a aba bab aba ababa ，

与之对应的 B 串中分别有 2 3 2 3 2 1 2 1 0 个子串和其相等，求和为 16 。

# Source


