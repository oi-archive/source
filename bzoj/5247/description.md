
# Description

<div class="content"><div>给定一个N个点的凸多边形以及一个凸多边形内部的点P。</div>
<div>请找一条最短的路线，从P出发并最后回到P，要求触碰多边形的每条边至少一次。</div>
<div>注意：触碰顶点时，算同时触碰了两侧对应的两条边。</div>
<p></p></div>

# Input

<div class="content"><div>每组数据第一行包含三个整数N,P_x,P_y(3&lt;=N&lt;=100,-10000&lt;=P_x,P_y&lt;=10000)，表示点数以及起点坐标。</div>
<div>接下来N行，每行两个整数x_i,y_i(-10000&lt;=x_i,y_i&lt;=10000)，按逆时针的顺序依次描述每个顶点的坐标。</div>
<div>输入数据保证任何两条相邻边的夹角小于180度，且P严格位于多边形内部。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，输出一行，包含数据编号和最短距离，保留2位小数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 0 0<br/>
-1 -1<br/>
1 -1<br/>
1 1<br/>
-1 1<br/>
3 10 1<br/>
0 0<br/>
30 0<br/>
0 20</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 5.66<br/>
Case 2: 36.73<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供试题">鸣谢Claris提供试题</a></p></div>

