
# Description

<div class="content"><div>1.管道从y轴负方向延伸到y轴正方向。 2.称x轴负方向为左边，x轴正方向为右边，z轴正方向为上边，z轴负方向</div>
<div>为下边。 3.管道是由若干四棱柱拼接而成，每个四棱柱的两个底面都是边长为1的正方形，且这两个底面都平行于</div>
<div>xoz平面。也就是说，对于管道的任何一个垂直于y轴的的截面，它都是正方形，只要知道右上角顶点的坐标(x,y,z</div>
<div>)就可以知道正方形剩下三个点的坐标(x-1,y,z), (x,y,z-1), (x-1,y,z-1)。 4.知道了管道右上方的折线，通过</div>
<div>向左平移1、再向下平移1、再向右平移1，再向上平移1，可以得到该管道的边界。所以给出管道右上方的折线的每</div>
<div>个顶点的坐标，我们就可以确定整个管道的形状。 对于gx的枪，有如下说明: 1.gx的枪沿一条直线射出一颗子弹</div>
<div>。我们把子弹视作是一个半径为r的圆，所以轨迹可以视作一个底面半径为r的狭长圆柱。对于某个y=y0的截面，如</div>
<div>果子弹能够完整地通过，称此处是被gx控制的。反之，子弹在接触目标前会发生偏折，因此该截面是不被控制的。</div>
<div>子弹刚好擦边而过的情况也算作可以通过。 2.gx站在y轴负方向的那一端，面向y轴正方向。gx的枪可以在管道外</div>
<div>任何位置以任何角度，从y轴负方向向y轴正方向进行瞄准。 现在面对这个蜿蜒曲折的管道，gx想知道他能控制的</div>
<div>最远截面的y坐标值是多少。</div></div>

# Input

<div class="content"><div>输入的第一行包含整数n和实数r。</div>
<div>接下来n行每行三个实数，第i行的三个实数表示第i个正方形右上角顶点的坐标(x, y, z)。</div>
<div>输入保证y坐标值是严格递增的。</div>
<div>3≤n≤20000, 0≤r≤0.5, -100000≤xi, yi, zi≤100000</div></div>

# Output

<div class="content"><p>输出一个实数，表示最远的控制点。保留三位小数。数据保证gx的子弹不能贯穿整个管道。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 0<br/>
0.0 -2.0 1.0<br/>
0.0 0.0 1.0<br/>
1.0 1.0 0.0<br/>
0.0 1.5 1.0<br/>
2.0 3.0 0.0</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.250<br/>
【样例说明1】<br/>
沿y轴正方向，最远可以控制到y=2.250</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

