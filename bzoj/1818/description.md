
# Description

<div class="content">无限大正方形网格里有n个黑色的顶点，所有其他顶点都是白色的（网格的顶点即坐标为整数的点，又称整点）。每秒钟，所有内部白点同时变黑，直到不存在内部白点为止。你的任务是统计最后网格中的黑点个数。
内部白点的定义：一个白色的整点P(x,y)是内部白点当且仅当P在水平线的左边和右边各至少有一个黑点（即存在x1 &lt; x &lt; x2使得(x1,y)和(x2,y)都是黑点），且在竖直线的上边和下边各至少有一个黑点（即存在y1 &lt; y &lt; y2使得(x,y1)和(x,y2)都是黑点）。

</div>

# Input

<div class="content">输入第一行包含一个整数n，即初始黑点个数。以下n行每行包含两个整数(x,y)，即一个黑点的坐标。没有两个黑点的坐标相同，坐标的绝对值均不超过109。

</div>

# Output

<div class="content">输出仅一行，包含黑点的最终数目。如果变色过程永不终止，输出-1。

</div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
0 2<br/>
2 0<br/>
-2 0<br/>
0 -2	</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
数据范围<br/>
36%的数据满足：n &lt; = 500<br/>
64%的数据满足：n &lt; = 30000<br/>
100%的数据满足：n &lt; = 100000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

