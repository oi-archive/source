
# Description

<div class="content"><div>作为水污染管理部门的一名雇员，你需要监控那些被有意无意倒入河流、湖泊和海洋的污染物。你的其中一项工作就是估计污染物对不同的水生态系统（珊瑚礁、产卵地等等）造成的影响。</div>
<div><img src="/source/bzoj/3973/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC8zMzMzMzMzMy5qcGc=.jpg" width="871" height="504" alt=""/></div>
<div></div>
<div>你计算所使用的模型已经在图1中被说明。海岸线（图1中的水平直线）为x轴，污染源位于原点(0, 0)。污染的蔓延呈半圆形，多边形代表了被波及的生态系统。你需要计算出生态系统被污染的面积，也就是图中深蓝色部分。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入文件包含仅包含一组测试数据。</div>
<div>
<div>每组测试数据第一行为两个整数n (3 &lt;= n &lt;= 100), r (1 &lt;= r &lt;= 1000)，n表示了多边形的顶点个数，r表示了污染区域的半径；</div>
<div>接下来n行，每行包含两个整数xi (-1500 &lt;= xi &lt;= 1500), yi (0 &lt;= yi &lt;=1500)，表示每个顶点的坐标，以逆时针顺序给出；</div>
<div>数据保证多边形不自交或触及自身，没有顶点会位于圆弧上。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>输出多边形被圆心位于原点、半径为r的半圆覆盖的面积。</div>
<div>答案的绝对误差不得超过10^-3。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 10<br/>
-8 2<br/>
8 2<br/>
8 14<br/>
0 14<br/>
0 6<br/>
-8 14</span></div>

# Sample Output

<div class="content"><span class="sampledata">101.576437872</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢talw001提供SPJ">鸣谢talw001提供SPJ</a></p></div>

