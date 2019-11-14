
# Description

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">有一个</span><span style="font-size: 12pt">N*M</span><span style="font-size: 12pt">的格子地图，地图上的格子有些是障碍，不能通过，有些不是障碍，有一个快乐程度，从每个格子可以移向上下左右四个格子。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">小月想从</span><span style="font-size: 12pt">[1,1]</span><span style="font-size: 12pt">格出发，旅游一些格子并回到</span><span style="font-size: 12pt">[1,1]</span><span style="font-size: 12pt">格，旅游的快乐程度等于经过的所有格子的快乐程度之和，小月想使得旅游的快乐程度之和尽可能大。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">注意：</span></div>
<div style="margin: 0cm 0cm 0pt 38.5pt; text-indent: -18pt"><span style="font-size: 12pt">1.<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">保证</span><span style="font-size: 12pt">[1,1]</span><span style="font-size: 12pt">格不是障碍</span></div>
<div style="margin: 0cm 0cm 0pt 38.5pt; text-indent: -18pt"><span style="font-size: 12pt">2.<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">除</span><span style="font-size: 12pt">[1,1]</span><span style="font-size: 12pt">格外不能重复走过同一格</span></div>
<div style="margin: 0cm 0cm 0pt 38.5pt; text-indent: -18pt"><span style="font-size: 12pt">3.<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">[1,1]</span><span style="font-size: 12pt">格的快乐程度只算一次</span></div>
<div style="margin: 0cm 0cm 0pt 38.5pt; text-indent: -18pt"><span style="font-size: 12pt">4.<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">快乐程度可能是负数</span></div>
<div style="margin: 0cm 0cm 0pt 38.5pt; text-indent: -18pt"><span style="font-size: 12pt">5.<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">若不能从</span><span style="font-size: 12pt">[1,1]</span><span style="font-size: 12pt">格出去并回来，则小月不会进行此次旅游。</span></div>
<div style="margin: 0cm 0cm 0pt 38.5pt; text-indent: -18pt"><span style="font-size: 12pt">6.<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">若旅游的快乐程度为负数，则小月不会进行此次旅游。</span></div>
<div style="margin: 0cm 0cm 0pt 38.5pt; text-indent: -18pt"><span style="font-size: 12pt">7.<span style="font: 7pt &#39;Times New Roman&#39;">      </span></span><span style="font-size: 12pt">若小月不会进行旅游，则旅游快乐程度为</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">。</span></div></div>

# Input

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">第一行两个正整数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 20.5pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">行，每行</span><span style="font-size: 12pt">M</span><span style="font-size: 12pt">个整数，第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">行第</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">列的数为</span><span style="font-size: 12pt">a[i][j]</span><span style="font-size: 12pt">。当</span><span style="font-size: 12pt">a[i][j]=0</span><span style="font-size: 12pt">时表示此格是障碍，否则表示快乐程度。</span></div></div>

# Output

<div class="content"><div style="text-indent: 20.5pt"><span style="font-size: 12pt">仅一行一个数，表示最大的旅游快乐程度。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 9 -1<br/>
-7 0 8<br/>
-1 -1 -1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
【数据规模和约定】<br/><br/>
100%的数据中：N,M&lt;=12,-10000&lt;=a[i][j]&lt;=10000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

