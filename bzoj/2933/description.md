
# Description

<div class="content"><div align="center"><span style="font-size: medium"><b> </b></span></div>
<div><span style="font-size: medium">一个人口统计办公室要绘制一张地图。由于技术的原因只能使用少量的颜色。两个有相同或相近人口的区域在地图应用相同的颜色。例如一种颜色<i>k</i>，则<b>A</b>(<i>k</i>) 是相应的数，则有：</span></div>
<ul type="disc">
    <li><span style="font-size: medium">在用颜色k的区域中至少有一半的区域的人口不大于<b>A</b>(<i>k</i>)</span></li>
    <li><span style="font-size: medium">在用颜色k的区域中至少有一半的区域的人口不小于<b>A</b>(<i>k</i>)</span></li>
</ul>
<div><span style="font-size: medium"><b>区域颜色误差</b>是该区域的人口与<b>A</b>(<i>k</i>)差的绝对值。<b>累计误差</b>是所有区域颜色误差的总和。我们要求出一种最佳的染色方案（累计误差最小）。</span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>任务</b></span></div>
<div><span style="font-size: medium">写一个程序：</span></div>
<ul type="disc">
    <li><span style="font-size: medium">读入每个区域的人口数</span></li>
    <li><span style="font-size: medium">计算最小的累计误差</span></li>
    <li><span style="font-size: medium">将结果输出</span></li>
</ul></div>

# Input

<div class="content"><div style="margin: auto 0cm"> </div>
<div><span style="font-size: medium">第一行有一个整数<i>n</i>，表示区域数，<i>10&lt; n &lt;3000</i>。在第二行中的数<i>m</i>表示颜色数，<i>2 &lt;= m &lt;= 10</i>。在接下来的<i>n</i>中每行有一个非负整数，表示一个区域的人口。人口都不超过<i>2^30</i>。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出一个整数，表示最小的累计误差</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">11<br/>
3<br/>
21<br/>
14<br/>
6<br/>
18<br/>
10<br/>
2<br/>
15<br/>
12<br/>
3<br/>
2<br/>
2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

