
# Content

某天，mzry1992一边思考着一个项目问题一边在高速公路上骑着摩托车。
一个光头踢了他一脚，摩托车损坏，而他也被送进校医院打吊针。

现在该项目的截止日期将近，他不得不请你来帮助他完成这个项目。

该项目的目的是维护一个动态的关于$x$的无穷多项式$F(x)=a_0\times x^{0}+a_1\times x^{1}+a_2\times x^{2}+\cdots$，这个多项式初始时对于所有$i$有$a_i=0$。

操作者可以进行四种操作：
1. 将$x^L$到$x^R$这些项的系数乘上某个定值$v$
2. 将$x^L$到$x^R$这些项的系数加上某个定值$v$
3. 将$x^L$到$x^R$这些项乘上$x$变量
4. 将某个定值$v$代入多项式$F(x)$，并输出代入后多项式的值，之后多项式还原为代入前的状况

经过观察，项目组发现使用者的操作集中在前三种，第四种操作不会出现超过$10$次。

mzry1992负责这个项目的核心代码，你能帮他实现么。

# Standard Input

输入的第一行有一个整数$n$代表操作的个数。

接下来$n$行，每行一个操作，格式如下：
* `mul L R v` 代表第一种操作
* `add L R v` 代表第二种操作
* `mulx L R` 代表第三种操作
* `query v` 代表第四种操作

对于$30\%$的数据：$N\leq 5000$，$0\leq L\leq R\leq 5000$，$0\leq v\leq 10^9$

另有$20\%$的数据：$N\leq 10^5$，$0\leq L\leq R\leq 10^5$，$0\leq v\leq 10^9$，没有`mulx`操作

剩下的$50\%$的数据：$N\leq 10^5$，$0\leq L\leq R\leq 10^5$，$0\leq v\leq 10^9$

# Standard Output

对于每个query操作，输出对应的答案，结果可能较大，需要模上$20130426$。

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
<tr><td>6
add 0 1 7
query 1
mul 0 1 7
query 2
mulx 0 1
query 3</td><td>14
147
588</td></tr></table>


# Constraints



# Note

操作一之后，多项式为$F(x)=7x+7$。

操作三之后，多项式为$F(x)=49x+49$。

操作五之后，多项式为$F(x)=49x^2+49x$。

# Source


