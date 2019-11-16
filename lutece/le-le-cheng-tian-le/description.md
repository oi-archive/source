
# Content

乐乐总是成天洋溢着**般的笑容，作为一名天才选手，他喜欢计算问题的概率与期望。但是有些时候结果的数值可能会太大，他担心凡人们无法理解他的意思，所以他会给出结果的模意义表示。现在他遇到了这样一个问题：初始时有一个空的字符串，每次向这个字符串末尾添加一个字符。添加的这个字符有$\frac{x}{x+y}$的概率是'a'，有$\frac{y}{x+y}$的概率是'b'，当这个字符串里至少有k个"ab"子序列时("aab"里面有两个“ab”子序列)，停止向这个字符串末尾添加字符。请问停止时，这个字符串中的"ab"子序列的期望个数。（输出答案在模$1e9+7$意义下的结果)

# Standard Input

输入三个数字$k$ $(1 \leq k \leq 1000), x, y (1 \leq x , y \leq 1000000)$

# Standard Output

输出结束时字符串中"ab"子序列的期望个数（在模$1e9+7$意义下的结果）

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
<tr><td>1 1 1</td><td>2</td></tr><tr><td>3 1 4</td><td>370000006</td></tr><tr><td>160 651424 289388</td><td>658727861</td></tr></table>


# Constraints



# Note

注意：逆元运算同样满足四则运算封闭！即当$x、y、z$分别是$a,b,\frac{a*b}{a+b}$的逆元时，有$x + y == z$

# Source


