
# Description

<div class="content"><div>平面的n条直线将平面分割成了若干区域，给出m 个点，求每个点所区域的面积。为了防止出现面积无穷大的情况</div>
<div>，有额外的四条直线框定了平面区域的大小，分别是x=L, y=L, x=-L, y=-L。其中L是给定的正实数，所有的点都</div>
<div>在这个框定的区域内。另外为了防止精度问题，任意一个点到任意一条直线的距离&gt;10^-7。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数和一个正实数，n, m, L，意义如上所述。 </div>
<div>第2~n+1行每行三个实数 A, B, C表示直线的方程为Ax+By+C=0。 </div>
<div>第n+2~n+m+1行每行两个实数 x, y 表示点的坐标。</div>
<div>对于100%的数据,输入数据的绝对值&lt;=10^7且最多保留2位小数，n&lt;=500,m&lt;=100000。 </div>
<div></div>
<div></div>
<div></div></div>

# Output

<div class="content"><div>按输入的顺序输出每个点所在的区域面积，每个一行，保留 2位小数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 4 3 <br/>
1 1 -1 <br/>
-1 1 -1 <br/>
0 2 <br/>
-2 1 <br/>
2 1 <br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">4.00 <br/>
8.50 <br/>
8.50 <br/>
15.00</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

