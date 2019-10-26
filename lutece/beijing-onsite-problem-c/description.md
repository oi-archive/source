
# Content

现有两个等长的串 s 和 t，长度不超过110，两串字符都只含有{1, 2, 3, 4, 5, 6}

现有两种操作：1. 将t的一个字符变为另一个字符；2. 将t的一种字符全部变为另一种字符。注意变换后的字符也只能属于字符集{1, 2, 3, 4, 5, 6}

现在给出100组case，每组给出两个串s, t，现问，可不断用上述两种操作，t 需最少多少步可以变为 s ？

# Standard Input

最多100组case

每组给出两行字符串s, t，1 <= |s|, |t| <= 110，|s| = |t|，s, t 都只含有 {1, 2, 3, 4, 5, 6}.

# Standard Output

对于每组数据，输出一行答案，表示最少步数，使得 t 变为 s

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
<tr><td>22345611
12345611
2234562221
1234561221
2234562211
1234561111
22345622112
12345611111
654321654321654321654321
123456123456123456123456</td><td>1
2
3
3
11</td></tr></table>


# Constraints



# Note



# Source


