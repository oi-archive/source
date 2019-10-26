
# Content

给你一个只包含正号(`+`)负号(`-`)加(`+`)减(`-`)乘(`*`)整除 (`/`)，括号(`(`和`)`)还有数字(`0123456789`)和恰好一个问号(`?`)的等式，求问号的值，使得等式成立。

注意，有前导0的数字算非法。

# Standard Input

一个等式，长度不超过$400$，并且有且只有一个问号(`?`).

# Standard Output

取代了问号之后的等式，如果有多组解，输出最小字典序解，如果无解，输出`-1`。

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
<tr><td>?++3=4
</td><td>1++3=4
</td></tr><tr><td>1?3=4
</td><td>1+3=4
</td></tr></table>


# Constraints



# Note



# Source


