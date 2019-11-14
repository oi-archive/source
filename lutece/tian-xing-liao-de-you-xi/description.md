
# Content

###天行健，君子以自强不息。地势坤，廖爷以厚德载物

一日在喵哈哈村，天行廖和沈宝宝正在玩一个游戏。

天行廖分别在$N$个纸片上写上一个数字，并放到一个盒子中。

现在沈宝宝要从盒子中抓出任意张纸片。

如果沈宝宝抓出的纸片上的数字$A\_{i1}$,$A\_{i2}$,....$A\_{ik}$满足$A\_{i1}$ & $A\_{i2}$ & ....$A\_{ik}$$ = 0$ ( $i\_{1} < i\_{2}  … < i\_{k}$)，那么天行廖赢得这次游戏的胜利，否则沈宝宝赢。

# Standard Input

第一行输入$1$个整数$N。$($1 \leq N \leq 10^6$)

第二行输入$N$个整数$A\_1，A\_2....A\_N$。($1 \leq A\_i \leq 10^6 $)

# Standard Output

输出获胜的方案数量。因为结果可能很大，输出答案对$10^9+7$取模的结果即可。

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
2 3 3
</td><td>0
</td></tr><tr><td>4
0 1 2 3
</td><td>10
</td></tr><tr><td>6
5 2 0 5 2 1
</td><td>53
</td></tr><tr><td>2
0 0
</td><td>3
</td></tr></table>


# Constraints



# Note

对于第$4$组样例，三组合法的解是$( A\_1 ) , ( A\_2 ) , ( A\_1，A\_2 )$

# Source


