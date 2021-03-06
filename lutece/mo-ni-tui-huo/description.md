
# Content

模拟退火是什么？

    模拟退火是一种通用概率算法，用来在一个大的搜寻空间内找寻命题的最优解，在大多数几何，或者最大值最小值优化问题上，这个算法很有见效。

    “模拟退火”的原理也和金属退火的原理近似：我们将热力学的理论套用到统计学上，将搜寻空间内每一点想像成空气内的分子；分子的能量，就是它本身的动能；而搜寻空间内的每一点，也像空气分子一样带有“能量”，以表示该点对命题的合适程度。算法先以搜寻空间内一个任意点作起始：每一步先选择一个“邻居”，然后再计算从现有位置到达“邻居”的概率。

    模拟退火算法可以分解为解空间、目标函数和初始解三部分。

    模拟退火的基本思想:

    (1) 初始化：初始温度T(充分大)，初始解状态S(是算法迭代的起点)， 每个T值的迭代次数L

    (2) 对k=1，……，L做第(3)至第6步：

    (3) 产生新解S′

    (4) 计算增量Δt′=C(S′)-C(S)，其中C(S)为评价函数

    (5) 若Δt′<0则接受S′作为新的当前解，否则以概率exp(-Δt′/(KT))接受S′作为新的当前解(k为波尔兹曼常数）.

    (6) 如果满足终止条件则输出当前解作为最优解，结束程序。

    终止条件通常取为连续若干个新解都没有被接受时终止算法。

    (7) T逐渐减少，且T->0，然后转第2步。

现在你懂模拟退火了吗？

那么我们出一道模拟退火的题目吧：

现在给你三个点A，B，C，你需要找到一点P，使得|PA|+2|PB|+3|PC|最小，然后输出这个距离。

# Standard Input

A,B,C 3个点的坐标

X1，Y1

X2，Y2

X3，Y3

所有数字都是整数，且在int范围内

# Standard Output

输出一个距离X，答案和标准答案相差在1e-6范围内的话，就算正确哦~

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
<tr><td>0 0
0 0
1 0</td><td>3.000000</td></tr></table>


# Constraints



# Note



# Source


