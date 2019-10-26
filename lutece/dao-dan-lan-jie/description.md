
# Content

某国为了防御敌国的导弹袭击，开发出一种导弹拦截系统。但是这种导弹拦截系统有一个缺陷：虽然它的第一发炮弹能够到达任意的高度，但是以后每一发炮弹都要高于前一发的高度。某天，雷达捕捉到敌国的导弹来袭，并观测到导弹依次飞来的高度，请计算这套系统最多能拦截多少导弹，同时，司令部想知道拦截下来的导弹的高度。拦截来袭导弹时，必须按来袭导弹袭击的时间顺序，不允许先拦截后面的导弹，再拦截前面的导弹。

# Standard Input

第一行是一个整数$t$,代表case数。
对于每一个case，第一行是一个整数$n(1 \leq n \leq 100000)$；
第二行是$n$个非负整数，表示第$n$枚导弹的高度，按来袭导弹的袭击时间顺序给出，以空格分隔。数据保证高度不会超过$100000$.

# Standard Output

对于每一个case,第一行输出最多能拦截的导弹数，第二行按来袭顺序输出拦截下来的导弹的高度构成的序列，以一个空格隔开。若有不止一种方法可以拦截最多的导弹，输出字典序最小的。

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
5
1 6 3 5 7</td><td>4
1 3 5 7</td></tr></table>


# Constraints



# Note



# Source


