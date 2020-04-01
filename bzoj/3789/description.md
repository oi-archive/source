
# Description

<div class="content"><div></div>
<div>
<div>n个城市和m条单向道路构成一个有向图，每条道路e上有整数积雪量We。一辆扫雪车每天从城市s开到t，经过一条道路一次就将其雪量减1（不能走雪量为0的道路）。有些道路（称为重要道路）必须清空积雪，这些道路的导出子图是包含s的弱连通图。求扫雪车工作天数的最大值。或判断无解。</div>
<div>弱连通图：将有向图的所有的有向边替换为无向边，所得到的图称为原图的基图。如果一个有向图的基图是连通图，则有向图是弱连通图。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div></div>
<div>第一行四个数n，m，s，t。</div>
<div>下面m行，每行四个数x，y，w，t。表示这条道路连接的两个城市，积雪量，和道路种类。若t为0则是普通道理，t为1则是重要道路。</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>扫雪车工作天数的最大值。或判断无解，输出0。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 7 1 4 <br/>
1 2 3 1 <br/>
2 1 100 0 <br/>
2 4 1 0 <br/>
1 3 1 0 <br/>
3 4 4 0 <br/>
2 3 2 1 <br/>
1 4 2 0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div>2 ≤ n ≤ 100; 0 ≤ m ≤ 5000; 1 ≤ s,t ≤ n; s ≠ t </div><br/>
<div>1 ≤ xi,yi ≤ n; xi ≠ yi; 0 ≤ wi ≤ 100; 0 ≤ ti ≤ 1 </div><br/>
</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

