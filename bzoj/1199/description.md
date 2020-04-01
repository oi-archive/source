
# Description

<div class="content"><div>汤姆是个好动的孩子,今天他突然对圆规和直尺来了兴趣。于是他开始在一张很大很大的白纸上画很多很多的矩形</div>
<div>和圆。画着画着,一不小心将他的爆米花弄撒了,于是白纸上就多了好多好多的爆米花。汤姆发现爆米花在白纸上看</div>
<div>起来就像一个个点,有些点落在矩形或圆内部,而有些则在外面。于是汤姆开始数每个点在多少个矩形或圆内部。毕</div>
<div>竟汤姆还只是个孩子,而且点、矩形和圆又非常多。所以汤姆数了好一会都数不清,于是就向聪明的你求助了。你的</div>
<div>任务是：在给定平面上N个图形(矩形或圆)以及M个点后，请你求出每个点在多少个矩形或圆内部(这里假设矩形的</div>
<div>边都平行于坐标轴)。</div></div>

# Input

<div class="content"><div>第一行为两个正整数N和M</div>
<div>其中N表示有多少个图形(矩形或圆)，M表示有多少个点。</div>
<div>接下来的N行是对每个图形的描述，</div>
<div>具体来说，第i+1行表示第i个图形。</div>
<div>先是一个字母,若该字母为“r”，则表示该图形是一个矩形,</div>
<div>这时后面将有4个实数x1,y1,x2,y2，表示该矩形的一对对角顶点的坐标分别为(x1,y1)和(x2,y2)；</div>
<div>若该字母为“c”，则表示该图形是一个圆,</div>
<div>这时后面将有3个实数x,y,r,表示该圆以(x,y)为圆心并以r为半径。</div>
<div>最后M行是对每个点的描述，其中每行将有两个实数x,y,表示一个坐标为(x,y)的点。</div></div>

# Output

<div class="content"><div>包含M行,每行是一个整数,其中第i行的整数表示第i个点在多少个图形内部</div>
<div>(当某点在一个图形的边界上时，我们认为该点不在这个图形的内部)。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4                                       <br/>
r 1.015 0.750 5.000 4.000                 <br/>
c 6.000 5.000 2.020                       <br/>
r 6.500 7.200 7.800 9.200                 <br/>
3.500 2.500<br/>
4.995 3.990<br/>
2.300 8.150<br/>
6.900 8.000</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

