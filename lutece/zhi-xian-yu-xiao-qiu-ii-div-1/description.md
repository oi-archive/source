
# Content

平面直角坐标系内，有$M$种不同的小球，第$k$种小球的个数记为$A_{k}$ ，第$k$种小球一个球的价值记为$P_{k}.$  $P_{1}=1,P_{k}=\sum_{i = 1}^{k - 1}P_iA_i(k \geq 2)$，请你找出一条直线，使这条直线上小球的总价值最大。

# Standard Input

* 第一行为一个整数$M$，代表小球的种类数。
* 接下来输入由$M$部分组成，按顺序依次描述第$1$种小球到第$M$种小球的信息。
* 每部分第一行为一个整数$A_{i}$， 代表第$i$种小球的个数。
* 接下来$A_{i}$ 行，每行两个整数$x_{b},y_{b}$，代表第$i$种小球的横、纵坐标。
* 小球的大小忽略不计，保证没有两个小球在同一位置。
* 数据范围：
* $1 \leq M \leq 50$
* $1 \leq A_{i} \leq 100$
* $-10^9 \leq x_{b},y_{b} \leq 10^9$

# Standard Output

输出仅一行，求得的最大小球总价值%$10^9+7$的结果。

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
1
0 0
1
1 1
2 
2 2
3 3</td><td>6</td></tr><tr><td>3
3
3 3
4 4
5 5
4
1 1
1 2
2 4
3 6
3
0 0
2 2
4 8</td><td>39</td></tr></table>


# Constraints



# Note

* 样例$1$，选取直线$y=x$，该直线上有第$1$种球$1$个，价值为$1$；有第$2$种球$1$个，价值为$1$；有第$3$种球$2$个，价值为$2$；总价值$=1×1+1×1+2×2=6$达到最大。
* 样例$2$，选取直线$y=2x$，该直线上有第$2$种球$3$个，价值为$3$；有第$3$种球$2$个，价值为$15$；总价值$=3×3+15×2=39$达到最大。

# Source


