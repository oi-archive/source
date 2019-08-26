
# Description

<div class="content"><div>A国是一个拥有n个城市的国家，其中城市s是A国的首都。</div>
<div>A国还有m条道路，每条道路连着两个不同的城市，但是一对城市间可能有多条道路。每一条道路都有它的长度，一条道路的通行时间与一条道路的长度成正比。</div>
<div>你作为A国的统治者，设计出了一种统计城市重要程度的方法：</div>
<div>1、一条道路的重要度为：在这条道路不能使用的情况下，到首都s的最短时间会变长的城市的数目。</div>
<div>2、一个城市的重要度为：以它作为一端的所有道路的重要度的和。</div>
<div>现在，你知道了A国的道路连接情况，你需要计算出每一个城市的重要度。</div>
<p></p></div>

# Input

<div class="content"><div>第一行，两个整数n,m，表示有A国有n个城市及m条道路。</div>
<div>第2~m+1行，每行三个整数u,v,l，描述了一条道路的两个端点城市及长度。</div>
<div>第m+2行，一个整数s，表示A国首都的编号</div>
<p></p></div>

# Output

<div class="content"><p><a id="fck_paste_padding">﻿</a>n行，每行一个整数，第i行为编号i的城市的重要度。 </p>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 3<br/>
2 3 4<br/>
3 4 5<br/>
4 1 2<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
0<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span lang="EN-US" style="line-height: 18px; text-indent: 28px; font-family: &#39;Times New Roman&#39;;">100%</span><span style="line-height: 18px; text-indent: 28px; font-family: 宋体;">的数据，</span><span lang="EN-US" style="line-height: 18px; text-indent: 28px; font-family: &#39;Times New Roman&#39;;">1&lt;=n&lt;=100000</span><span style="line-height: 18px; text-indent: 28px; font-family: 宋体;">，</span><span lang="EN-US" style="line-height: 18px; text-indent: 28px; font-family: &#39;Times New Roman&#39;;">1&lt;=m&lt;=200000</span><span style="line-height: 18px; text-indent: 28px; font-family: 宋体;">，</span><span lang="EN-US" style="line-height: 18px; text-indent: 28px; font-family: &#39;Times New Roman&#39;;">1&lt;=l&lt;=10^8</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

