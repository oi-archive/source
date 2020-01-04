
# Content

飞机票编码规则是：前面有不超过 6 位代表航空公司的英文字符，接着有不超过 18 位的数字，例如 CA47715497443。为了方便验证，最后一位数字必须与以其他的数字为整体除以 7 后的余数相匹配。（例如，4771549744 除以 7 的余数为
 3 。）你的任务是判断给定的飞机票是否有效。

# Standard Input

含多组测试数据，输入首先是一个整数 T 表示测试数据组数(0<T<= 300)。随后有 T 组测试数据，每组占一行。

# Standard Output

对应每组测试数据，输出 "Yes" 或 "No"。

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
<tr><td>2
CA47715497443
WL3562912709</td><td>Yes
No</td></tr></table>


# Constraints



# Note



# Source


