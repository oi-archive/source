
# Content

一天，蒟蒻`forgottencsc`正在做概率论与数理统计的复习题，然而潇神`Eterna_King`在`forgottencsc`复习的时候用魔法把他书上的数据改了很多遍。连方差都不会算`forgottencsc`的考试在即，但是他想完成的复习题量却非常大，聪明的你能在时间限制内帮他及时完成复习计划吗？

`forgottencsc`不会做的那些题的形式都类似于：求出编号在$[L,R]$之间的所有样本 $X_i(L \leq i \leq R)$的方差$S^2$。

因为他不会算除法，所以你需要输出方差乘上样本个数的`平方`并对$10^9+7$取模的结果。

如样本为$1,2,3$，那么你需要输出$[\frac{(1-2)^2+(2-2)^2+(3-2)^2}{3}\times3^2]\%(10^9+7)=6$。

# Standard Input

第一行有两个数$N,Q$。意为总共有$N$个样本并且下面有$Q$个`forgottencsc`不会的复习题或潇神的修改。

第二行有$N$个数，第$i$个数$a_i$即为第$i$个样本的初始值。

接下来$Q$行，每行第一个数为$o$。

当$o=1$时，接下来有三个数$L,R,k$，代表潇神将编号在区间$[L,R]$内的样本全部加上了$k$。

当$o=2$时，接下来有三个数$L,R,k$，代表潇神将编号在区间$[L,R]$内的样本全部乘上了$k$。

当$o=3$时，接下来有三个数$L,R,k$，代表潇神将编号在区间$[L,R]$内的样本全部变成了$k$。

当$o=4$时，接下来有两个数$L,R$，代表`forgottencsc`碰到了一道不会的题，此时你需要输出这个区间中的方差乘上这个区间中的样本个数的平方后对$10^9+7$取模的结果。由方差公式易知，结果必为一个非负整数。

# Standard Output

对于每一道`forgottencsc`不会的题，即$o=4$的询问，输出相应的结果。

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
<tr><td>3 4
0 0 0
1 1 3 1
2 2 3 2
3 3 3 3
4 1 3</td><td>6</td></tr></table>


# Constraints

$1\leq N,Q\leq 10^5$

$0\leq a_i,k \leq 10^9$

对每个问题/修改有：

$1 \leq L \leq R \leq N$

$1 \leq o \leq 4$

# Note

想一想，三种修改操作就一定要三种懒标记吗？

注意：本题中的方差定义与教科书或维基百科中的方差定义可能存在区别！

以下为本题中方差的定义：

$\displaystyle S^2=\frac{1}{n}\left[\sum_{i=1}^{n}{(X_i-\bar{X})^2}\right]$

$\displaystyle \bar{X}=\frac{1}{n}\sum_{i=1}^{n}{X_i}$

# Source


