<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个平面中有n个顶点和m条直线段，第i个顶点的坐标为(xi,yi)第j条直线段连接顶点uj和顶点vj，权值为hj，除顶点uj和vj外直线段j不经过其他的顶点。任意两条直线段如果存在公共点，则该公共点一定是一个顶点，此时这两条直线段都会连接这个顶点。对于任意的两个顶点x和y，总是可以找到一顶点序列al,a2，…，ak使得al=x，ak=y且对于任意l≤i&lt;k满足ai和a[i+1]被一条直线段直接连接。</p>
<p><br>这m条直线段将整个平面分成了若干个区域，其中只有一个区域是无穷大的，其余均是有界的，我们称无穷大的区域为禁区。</p>
<p><br>现在给出q次询问，每次给定平面中的任意两个不是顶点且分别不在任意一条直线段上的点A和B，请画一条曲线连接A和B，要求曲线不能经过禁区以及任何顶点，并使得穿过的直线段中权值最大的尽可能小。你需要对每次询问回答<br>这个值最小为多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个正整数n、m，分别表示顶点数和直线段数。<br>接下来n行，每行两个整数，这部分中第i行（总第i+1行）的两个整数xi,yi为顶点i的坐标，<br>接下来m行，每行三个正整数u、v、h，表示有一条直线段连接项点u和顶点v，权值为h。其中u≠v。<br>接下来的一行，有一个正整数q．表示询问数量。<br>接下来q行，每行四个实数Ax,Ay,Bx,By，表示一组两个点的坐标分别为(Ax,Ay)和(Bx,By)的询问。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出q行，每行一个正整数，依次表示每个询问的答案。特别的，若不需要跨过任何一条边即可到达，请输出0；若不存在合法的曲线，请输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 12<br>1 1<br>1 2<br>1 3<br>2 1<br>2 2<br>2 3<br>3 1<br>3 2<br>3 3<br>1 2 10<br>2 3 10<br>3 6 10<br>6 9 10<br>9 8 10<br>8 7 10<br>7 4 10<br>4 1 10<br>2 5 3<br>5 8 2<br>5 6 4<br>4 5 1<br>3<br>1.5 1.5 2.5 2.5<br>1.5 2.5 2.5 1.5<br>0.5 0.5 1.5 1.5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>3<br>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于全部数据，均满足5≤n,m,q≤100,000，所有直线段的权值不会超过10^9。<br>所有询问坐标均为不超过10^7的实数，且保证是0.5的整数倍。</p>
</div>
</div>