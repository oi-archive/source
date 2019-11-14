
# Content

编码特别的有趣，特别是在喵哈哈村里的编码。

因为喵哈哈村的对编码有一些特别的限制。

假设某一个编码为$S\_{1},S\_{2},S\_{3},S\_{4}....,S\_{l}$，其中$S\_{i}$表示这是编码中的第$i$位。

那么在喵哈哈村中，它应该满足以下要求：

1.$l$ 不应该超过$m$，即编码的长度不超过$m$

2.每一个位置$S\_{i}$的取值范围为$[1,ri]$

对于所有的编码而言，应该满足任意一个编码都不是另外一个编码的前缀。

现在你就需要在满足以上条件的情况下，构造出$n$个编码，使得$\sum\_{1}^{n}w\_{i}\*l\_{i}$ 最小。

$l\_{i}$即第$i$个编码的长度。

# Standard Input

第一行两个整数 $n$,$m$($1<=n,m<=500$)

第二行$n$个整数$w\_{1},w\_{2}......w\_{n}$($1<=wi<=500$)

第三行$m$个整数$r\_{1},r\_{2}.....r\_{m}$($1<=ri<=500$}

保证$r\_{1},r\_{2}.....r\_{m}$的乘积大于等于$n$

# Standard Output

一个整数，表示最小值是多少。

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
<tr><td>2 2
4 3
2 1</td><td>7</td></tr><tr><td>3 2
1 2 4
2 2</td><td>10</td></tr></table>


# Constraints



# Note

第一个样例的两个编码为：{1}，{2}，答案就是4+3=7

第二个样例的三个编码为：{1,1}，{1,2}，{2}，答案就是2\*1+2\*2+4 = 10

# Source


