
# Content

Fish是一条生活在海里的鱼，有一天他很无聊，于是他去捡了人类扔进海里的垃圾，打算用这些来玩些什么。

他从捡回来的垃圾堆里找到了$n$根火柴棍，他想把这些火柴棍拼成一个长度为$m$的十进制数，每个数字的拼法如下图所示。

![title](/source/lutece/huo-chai-gun-shu-zi-er/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTI2Ny8yMDE1MTIxMzAwMzgyNzMzNTUucG5n.png)

他想拼出来的数尽量大，这该怎么拼呢？

聪明的你，肯定知道该如何利用这$n$根木棒得到最大的$m$位数。

那就快告诉Fish吧~

当然，不能有前导$0$哦。

而且木棍得全部用完！

# Standard Input

第一行输入两个整数,$n$,$m$

满足 $1<=n,m<=10^5$

# Standard Output

将这$m$位数输出

如果不能得到任何一个$m$位数，请输出$-1$

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
<tr><td>5 2</td><td>71</td></tr><tr><td>1 1000</td><td>-1</td></tr></table>


# Constraints



# Note

第一个样例解释：

一开始，Fish有5个木棒，Fish用了3根木棒摆成了7的模样，用2根木棍摆成了1的模样

合在一起，组成了 71 这个数！

Fish想了想，这的确是它**恰好**用完5根木棍后，能够组成的最大的数。

by lyhypacm

# Source


