
# Content

复读机在经过上一次的试探之后，开始狂欢。复读机并不满足于添加前缀复读，他们还想添加后缀复读，他们还想超级加倍复读，现在准备复读的复读机会找到上一个复读机复读的字符串 $S$ （第一个复读机找到的串为空）， 并且进行如下操作中的一个：

- 在 $S$ 的开头添加一个字符
- 在 $S$ 的末尾添加一个字符
- 把 $S$ 反转添加到 $S$ 开头
- 把 $S$ 反转添加到 $S$ 末尾

现在群管理得到了最后一个复读机复读的文本串 $T$ （$T$ 仅包含大写字符 $A,B,C,D$）。可以开始准备子弹了，每有一个复读机参与复读，准备一颗子弹枪毙，问至少要准备多少颗子弹。

# Standard Input

第一行包含一个正整数 $K(1\le K \le 10^6)$ 测试数据的组数。 

接下来 $K$ 行，每行包含字符串 $T$ 代表最后一个复读机复读的文本串，数据保证 $\sum_{K}|T|\le 10^6$。

# Standard Output

输出包含 $K$ 行，每行输出至少准备多少颗子弹

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
<tr><td>1
ABABA</td><td>5</td></tr><tr><td>1
ABBBBA</td><td>4</td></tr></table>


# Constraints



# Note



# Source


