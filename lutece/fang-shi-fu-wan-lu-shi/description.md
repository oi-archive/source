
# Content

方师傅最近迷上了玩炉石传说，他发现这个游戏里有很多卡牌，每张卡牌有个名字。卡牌的不同的组合有不同的能量。

每张卡牌的名字由$4$个字母`A`,`G`,`C`,`T`组成。

方师傅开始了对战，现在他有$N$张卡牌，他决定每次从里面选出$2$张牌来组合，选出来组合后，方师傅将得到这$2$张牌的最长公共前缀的长度的能量。

例如：他选择了`AGTT`和`AGTC`两张牌，他将得到$3$的能量。

现在方师傅想问你，他的这$N$张卡牌，要怎么样组合才能发挥出最大的能量？最大的能量是多少？

# Standard Input

输入第$1$行包含$1$个数$N$，代表方师傅的卡牌数量

接下来$N$行，每行包含$1$个字符串，代表方师傅的卡牌的名字

数据保证，$N\leq 10^{5}$，输入的字符串总长度不超过$10^{6}$，字符串只包含$A$,$G$,$C$,$T$四种字符。

# Standard Output

输出第$1$行包含$1$个数$P$，代表方师傅能得到的最大能量

接下来$\lfloor \frac{N}{2} \rfloor$ 行，每行包含$2$个整数$a$ $b$，代表方师傅每次的组合方式

你的输出需保证，每个整数仅出现$1$次。

如果有多解，请输出任意一个。

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
<tr><td>4
AGCT
AGT
AGC
AG</td><td>5
1 3
2 4</td></tr><tr><td>3
AG
G
AG</td><td>2
1 3</td></tr></table>


# Constraints



# Note



# Source


