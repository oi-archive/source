
# Description

<div class="content"><p><span style="font-size: medium">　给定一个边带正权的连通无向图G=(V,E)，其中N=|V|，M=|E|，N个点从1到N依次编号，给定三个正整数u，v，和L (u≠v)，假设现在加入一条边权为L的边(u,v)，那么需要删掉最少多少条边，才能够使得这条边既可能出现在最小生成树上，也可能出现在最大生成树上？<br/>
</span></p>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体"><span style="font-size: medium">　</span></div></div>

# Input

<div class="content"><p></p>
<p></p>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体">
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体"></div>
</div>
<p></p>
<p><br/>
</p>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体">　<font size="4">　第一行包含用空格隔开的两个整数，分别为N和M；<br/>
　　接下来M行，每行包含三个正整数u，v和w表示图G存在一条边权为w的边(u,v)。<br/>
　　最后一行包含用空格隔开的三个整数，分别为u，v，和 L；<br/>
　　数据保证图中没有自环。<br/>
</font>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体"><span style="font-size: medium">　</span></div>
</div></div>

# Output

<div class="content"><p><font size="4">　输出一行一个整数表示最少需要删掉的边的数量。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
3 2 1<br/>
1 2 3<br/>
1 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于20%的数据满足N ≤ 10，M ≤ 20，L ≤ 20；<br/><br/>
　　对于50%的数据满足N ≤ 300，M ≤ 3000，L ≤ 200；<br/><br/>
　　对于100%的数据满足N ≤ 20000，M ≤ 200000，L ≤ 20000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day1">2012国家集训队Round 1 day1</a></p></div>

