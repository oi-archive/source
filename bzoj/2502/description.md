
# Description

<div class="content"><div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">滑雪场坐落在</span><span style="font-size: 12pt">FJ</span><span style="font-size: 12pt">省西北部的若干座山上。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">从空中鸟瞰，滑雪场可以看作一个有向无环图，每条弧代表一个斜坡<span style="color: red">（即雪道）</span>，弧的方向代表斜坡下降的方向。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">你的团队负责每周定时清理雪道。你们拥有一架直升飞机，每次飞行可以从总部带一个人降落到滑雪场的某个地点，然后再飞回总部。从降落的地点出发，这个人可以顺着斜坡向下滑行，并清理他所经过的雪道。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">由于每次飞行的耗费是固定的，为了最小化耗费，你想知道如何用最少的飞行次数才能完成清理雪道的任务。</span></div>
<div style="text-indent: 21pt">
<div style="margin: 13pt 0cm; line-height: normal"></div>
</div></div>

# Input

<div class="content"><div style="text-indent: 21pt">
<div style="margin: 13pt 0cm; line-height: normal"></div>
<span style="font-size: 12pt">输入文件的第一行包含一个整数</span><i><span style="font-size: 12pt">n</span></i><span style="font-size: 12pt"> (2 &lt;= <i>n</i> &lt;= 100) – </span><span style="font-size: 12pt">代表滑雪场的地点的数量。接下来的</span><i><span style="font-size: 12pt">n</span></i><span style="font-size: 12pt">行，描述</span><span style="font-size: 12pt">1~<i>n</i></span><span style="font-size: 12pt">号地点出发的斜坡，第</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">行的第一个数为</span><i><span style="font-size: 12pt">m<sub>i</sub></span></i><span style="font-size: 12pt"> (0 &lt;= <i>m<sub>i</sub></i> &lt; <i>n</i>) </span><span style="font-size: 12pt">，后面共有</span><i><span style="font-size: 12pt">m<sub>i</sub></span></i><span style="font-size: 12pt">个整数，由空格隔开，每个整数</span><i><span style="font-size: 12pt">a<sub>ij</sub></span></i><span style="font-size: 12pt">互不相同，代表从地点</span><i><span style="font-size: 12pt">i</span></i><span style="font-size: 12pt">下降到地点</span><i><span style="font-size: 12pt">a<sub>ij</sub></span></i><span style="font-size: 12pt">的斜坡。每个地点至少有一个斜坡与之相连。</span></div></div>

# Output

<div class="content"><div style="margin: 13pt 0cm; line-height: normal"> </div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">输出文件的第一行是一个整数</span><i><span style="font-size: 12pt">k</span></i><span style="font-size: 12pt"> – </span><span style="font-size: 12pt">直升飞机的最少飞行次数。</span></div>
<div style="text-indent: 21pt">
<div style="margin: 13pt 0cm; line-height: normal"></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
1 3<br/>
1 7<br/>
2 4 5<br/>
1 8<br/>
1 8<br/>
0<br/>
2 6 5<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

