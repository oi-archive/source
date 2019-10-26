
# Content

![title](/source/lutece/hei-hong-mei-fang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTYxMC8yMDE3MDUwNTE2MzAyOTQxNTUuanBn.jpg)

我们知道，一副扑克有黑桃、红桃、梅花、方块四种花色。

现在你把$N$张扑克排成一行，每个位置都可以选择放置四种花色中的一种，只要这一行中出现了一组连续四张扑克牌花色各不相同的情况，就称该种排法为“卿式扑克序列”。

请你计算，对于$N$张扑克排成一行的$4^N$种排法中，共有多少种“卿式扑克序列”呢？

# Standard Input

一个整数$N(4 \leq N \leq 10^{18})$

# Standard Output

$N$张扑克排成一行的“卿式扑克序列”总数对$10^9+9$取模的结果。

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
<tr><td>4</td><td>24</td></tr><tr><td>5</td><td>168</td></tr></table>


# Constraints



# Note

样例$1$，以$A$代表黑桃，$B$代表红桃，$C$代表梅花，$D$代表方块，共有以下$24$种“卿式扑克序列”：

$ABCD\ ABDC\ ACBD\ ACDB\ ADBC\ ADCB$
 
$BACD\ BADC\ BCAD\ BCDA\ BDAC\ BDCA$

$CABD\ CADB\ CBAD\ CBDA\ CDAB\ CDBA$

$DABC\ DACB\ DBAC\ DBCA\ DCAB\ DCBA$

# Source


