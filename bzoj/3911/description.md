
# Description

<div class="content"><div>在这个任务中，你的目标是掠夺商队。</div>
<div></div>
<div>在沙漠中有n个绿洲（对于我们而言，它们在平面上的点）。有时商队从一个绿洲到另一个绿洲。为了掠夺它们，你应该预测其路径。但如何做呢？Nomad给出了解决方案。商队的速度是恒定的，他们尽量减少在绿洲外的最长时间。所以，你可以得出结论，即最佳路径是折线。</div>
<div></div>
<div>给定绿洲的坐标和m对商队的线路，出发点为编号为si的绿洲，目的地为编号为ti的绿洲，将最佳路径的最大长度输出。保证所有绿洲位置不同。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行一个正整数n为绿洲的数量</div>
<div></div>
<div>接下来n行，每行两个整数x,y表示绿洲在二维平面上的点坐标</div>
<div></div>
<div>接下来一行为一个正整数m为商队数量</div>
<div></div>
<div>接下来m行，每行两个正整数si,ti，为第i个商队的起点和终点</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>输出m行，每行一个6位小数，为最佳路径上的最大长度</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 0<br/>
50 10<br/>
150 0<br/>
3<br/>
1 2<br/>
1 3<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">50.990195<br/>
100.498756<br/>
100.498756</span></div>

# Hint

<div class="content"><p></p><div>n,m&lt;=100000</div><br/>
<div>0&lt;=x,y&lt;100000</div><br/>
<div></div><br/>
<div>三角剖分</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By佚名上传
">By佚名上传<br/>
</a></p></div>

