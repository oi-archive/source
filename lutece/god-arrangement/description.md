
# Content

一个盒子里共有 $21$ 个小球，$15$个蓝色的，$6$个红色的。如果我们从其中随机地拿出两个，那么它们同为蓝色的概率是多大呢？聪明的你一定早就口算出来了，二分之一。

如果一个盒子里有 $N$ 个小球，其中蓝色的有 $M$ 个，如果随机从中取出两个小球都为蓝色的概率是二分之一，我们称这种组合为 God Arrangement ！

可以证明 $(4,3)$ 是规模最小的 God Arrangement （所谓规模，是指小球总数），接下来才是 $(21,15)$，如果你足够聪明，现在必然已经算出来了下一个 God Arrangement 是 $(120,85)$。

可是 God 不高兴了，他的美妙安排怎么能让一般人随意揣测？！于是他准备向你挑战，给你任意一个正整数 $G$，你能否快速求出规模大于 $G$ 的最小 God Arrangement。

# Standard Input

第一行是一个正整数 $T$（$T < 100$），表示需要测试的组数。

接下来有 $T$ 行数据，每行只有一个正整数 $G$（$0 < G < 10^{16}$）。

# Standard Output

对于每一个输入 $G$，对应输出一行结果 ，表示规模不小于 $G$ 的最小 God Arrangement的小球总数。

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
4
33</td><td>4
21
120</td></tr></table>


# Constraints



# Note



# Source


