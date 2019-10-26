
# Content

冬马被方师傅绑架了！！！

一天，春希收到了一个信封，里面有一张印有$8 \times 8$棋盘的纸，一个被加了密的U盘和一个便条。便条上写着：

***
冬马在我手上，如果你想救出冬马，U盘里就有我详细的地址，当然前提是你能解出密码！

你可以把这个棋盘分割成$n$块，每一次你可以从一棋盘上割下一块矩形，并让剩下的部分也是矩形，再将剩下的部分如此分割。

![title](/source/lutece/shen-mi-bang-jia-an/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODgxLzIwMTQwNTE2MjIxMzU3NjQyNS5qcGc=.jpg)

原棋盘每一格有一个分值，一块矩形的总分为其所含各格分值之和。你需要按上述方法将棋盘分成$n$块后，求出各矩形棋盘总分的均方差。我也不介意告诉你，所有均方差中的最小值就是U盘的密码，那么请挣扎吧！

平均数公式：$$\overline{x}=\frac{\sum\_{i=1}^{n}x\_i}{n}$$

均方差公式：$$\sigma=\sqrt{\frac{\sum\_{i=1}^{n}(x\_i-\overline{x})^2}{n}}$$

<p class="text-right">------方师傅留</p>
***

春希非常焦急的找到了你，希望你能找出这个最小值，救出冬马。

# Standard Input

第一行一个整数$n$，表示分割后的块数。$(1<n<15)$

第二行到第九行，每行八个小于$100$的非负整数，表示棋盘上相应格子的分值。

# Standard Output

一个数，表示求出的最小值。(四舍五入精确到小数点后三位)

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
1 1 1 1 1 1 1 3
1 1 1 1 1 1 1 1
1 1 1 1 1 1 1 1
1 1 1 1 1 1 1 1
1 1 1 1 1 1 1 1
1 1 1 1 1 1 1 1
1 1 1 1 1 1 1 0
1 1 1 1 1 1 0 3</td><td>1.633</td></tr></table>


# Constraints



# Note



# Source


