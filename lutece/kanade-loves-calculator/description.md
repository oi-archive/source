
# Content

纯音乐，请您欣赏。

——《[kanade](http://music.163.com/song?id=471934)》

---

Kanade 为了概率论与数理统计考试，以 14.8 的价格买了一个 XF-9991CN，这明显是假货，但是她发现这个计算器还是很好用。因为她发现这个计算器能解类似下面以 $x$ 为未知量的方程

$$
a^x\equiv b\pmod m
$$

计算器会输出最小满足以上方程的非负整数 $x$。如果不存在这样的 $x$，计算器会输出 `QAQ`。

因为几乎没有计算器提供这种功能，于是 Kanade 想测试一下这个功能是否合格。

你是一个一般通过的路人，现在你想帮助 Kanade 测试这个功能，作为回报 Kanade 会把店家网址给你。

# Standard Input

本题有多组数据，第一行一个整数 $T$，表示测试数据组数。

接下来 $T$ 行，每行包含三个整数 $a,b,m$，表示方程中的三个参数。

# Standard Output

输出 $T$ 行，每行包含一个非负整数，表示满足 $a^x\equiv b\pmod m$ 的最小非负整数 $x$。若不存在这样的 $x$ 则输出 `	QAQ`。

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
<tr><td>3
1 1 4
5 7 10
2 96 106</td><td>0
QAQ
22</td></tr></table>


# Constraints

$1\le a,b< m\le 10^9,1\le T\le 500$

# Note



# Source


