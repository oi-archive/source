
# Content

在$UESTC$，你会学到众多的$FT$，像$DFT$，$CTFT$，$DTFT$，$FFT$等，但是，这里，我们考虑一种名叫$CFT$的东西，它的作用与前面的不太一样，在这里，是将一个01串，映射为另一个等长的01串。

$$CFT :S1 -> S2, (S1,S2为01串)$$

$CFT$的映射规则有$m$条，在下面给出；同时，每计算一个$CFT$需要一定的时间$t$，现在给你初始的01串$S0$，其长度为$n$,并且元素全为0，即$00...0$，问你，至少需要多长的时间，可以通过$CFT$将$S0$变为$S1$,$S1$长度也为$n$,且元素全为1(即$11...1$)

# Standard Input

首行两个整数$n,m(1\le n \le 20, 1\le m \le 100000)$.

​接下来$m$行，每行包括两个01串(长度为$n$)和一个整数$s_i,w_i,t_i, (1\le t_i \le 1000000000)$，表示$s_i$经过$CFT$变为$w_i$需要$t_i$ 的时间

# Standard Output

如果不能得到$S1$，输出-1；

​否则输出将$S0$经过$CFT$变为$S1$所需最少时间。

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
<tr><td>3 5
000 110 2
000 010 4
000 101 2
110 111 1
000 111 3</td><td>3</td></tr></table>


# Constraints



# Note



# Source


