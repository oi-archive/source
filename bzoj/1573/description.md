
# Description

<div class="content"><p><span style="font-size: medium">Bessie学会了刺绣这种精细的工作。牛们在一片半径为d(1 &lt;= d &lt;= 50000)的圆形布上绣花. 它们一共绣了N (2 &lt;= N &lt;= 50000)条直线，每条直线连接布的边缘上的两个点(没有两条线通过边上同一个点)。 作为一只热爱数学的牛，Bessie 知道每条线的公式, ax + by + c = 0. a, b, 和 c 为整数(-1000000 &lt;= a &lt;= 1000000; -1000000 &lt;= b &lt;= 1000000; -1000000 &lt;= c &lt;= 1000000).没有两条线完全重合。 不幸的是, 一部分线不通过圆布的内部. 原点(0,0)在布的正中央, 所有边上的点离原点距离为d. 每条线的公式满足至少a,b中的一个非零. 对于牛来说，刺绣作品中线的交点越多，便越有价值。帮助Bessie计算在圆中相交的线的对数，也就是说交点与原点的距离小于d。注意如果三条线在圆内同一点相交,这算3对线。4线共点-&gt;6对线. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行: 两个空格分开的数, N 和 d 第2..N+1行: 第 i+1 行包含第i条线的参数: a, b 和 c </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第1行: 一行，包含一个数,为在园内相交的线的对数. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
1 0 0<br/>
0 1 0<br/>
<br/>
输入说明：<br/>
两条直线x=0和y=0.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">两条线在(0,0)相交, 明显离原点距离小于1. </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

