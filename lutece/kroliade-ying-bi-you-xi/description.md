
# Content

Krolia和Felix玩一个游戏。游戏一开始Krolia有$a$枚金币，Felix有$b$枚金币。游戏由若干局组成，每一局先掷一枚硬币，如果是正面Krolia给Felix一枚金币，反之Felix给Krolia一枚金币。假设每次抛硬币的结果只会是正面或者反面的二者之一，且两者出现的概率相等。一局结束后，如果输了金币的那一方无法给出金币，则游戏结束，否则进行下一局。问Krolia赢得游戏的概率是多少。

# Standard Input

有多组测试数据。输入的第一行是整数$T$($0 < T \leq 100$)，表示测试数据的组数。每一组测试数据只有一行，分别为整数$a$、$b$($0 \leq a,b \leq 100$)，相邻两数间有一个空格。该行没有其它多余的符号。

# Standard Output

一个小数，四舍五入到小数点后四位。

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
0 0
1 0</td><td>0.5000
0.6667</td></tr></table>


# Constraints



# Note

第一组样例中一局游戏之后游戏就必然结束了。

第二组样例中Krolia获胜的硬币序列为：
```
反
正反反
正反正反反
正反正反正反反
```
Krolia获胜的概率为：$0.5+0.5^3+0.5^5\cdots$

由等比数列求和公式可知Krolia的胜率为$\frac{2}{3}$。

该题是一个简单的结论题，请尝试猜测这个结论，然后大胆提交吧。

请使用double型数据来计算。

double型数据四舍五入到四位小数可以用`printf("%.4f",v);`来输出($v$是待输出的变量)。

# Source


