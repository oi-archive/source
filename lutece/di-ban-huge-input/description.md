
# Content

lxhgww的小名叫“小L”，这是因为他总是很喜欢L型的东西。小L家的客厅是一个$R\times C$的矩形，现在他想用L型的地板来铺满整个客厅，客厅里有些位置有柱子，不能铺地板。现在小L想知道，用L型的地板铺满整个客厅有多少种不同的方案？

需要注意的是，如下图所示，L型地板的两端长度可以任意变化，但不能长度为$0$。铺设完成后，客厅里面所有没有柱子的地方都必须铺上地板，但同一个地方不能被铺多次。

![title](/source/lutece/di-ban-huge-input/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDM3LzIwMTQwODE0MjAyOTEzNjgzMTUuanBn.jpg)

# Standard Input

输入的第一行包含两个整数，$R$和$C$，表示客厅的大小。($R\times C\leq 100$)

接着是$R$行，每行$C$个字符。`_`表示对应的位置是空的，必须铺地板；`*`表示对应的位置有柱子，不能铺地板。

# Standard Output

输出一行，包含一个整数，表示铺满整个客厅的方案数。由于这个数可能很大，只需输出它除以$20110520$的余数。

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
*_
__</td><td>1</td></tr><tr><td>3 3
___
_*_
___</td><td>8</td></tr></table>


# Constraints



# Note



# Source


