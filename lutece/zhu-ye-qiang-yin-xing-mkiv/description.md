
# Content

柱爷对金钱的掌控能力声名在外，连米达斯银行也想拉拢他当Entrepreneur。

但柱爷是个有原则的人。他发现了米达斯银行的阴谋，打算尽最大力量去破坏它，即从金融街的银行中回收尽可能多的钱。

金融街上有$N$个银行。对于第$i$间银行，它的坐标是$x_i$，有$v_i$的钱能被柱爷回收。**因为金融街是与现实分离的异空间，可能会有很多间银行位于同一坐标的不同时空内。**

米达斯银行也不是咸鱼，他们规定了只能从较小号数的银行才能到达较大号数的银行。而且对于第$i$间银行，只有从与坐标比它小$y_i$以内的银行才能到达它。即从满足以下条件的银行$j$能到达银行$i$，$x_i-y_i \leq x_j \leq x_i，j<i$。

柱爷可以从任意一间银行开始抢钱，请问他最多能抢多少钱。

# Standard Input

第一行一个数$N$，即有$N$间银行。

之后有$N$行，每行3个数$x_i$，$v_i$，$y_i$

数据保证：

* $1 \leq N\leq10^5$

* $1 \leq x_i,v_i,y_i\leq10^9$

# Standard Output

输出一个数，即柱爷最多能抢多少钱。

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
1 2 1
3 1 1
2 2 3</td><td>4</td></tr></table>


# Constraints



# Note



# Source


