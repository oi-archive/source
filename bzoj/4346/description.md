
# Description

<div class="content"><div>比特镇一共有n个房子，编号依次为1到n，这些房子通过n-1条无向道路连通在一起，形成了一棵树的结构。</div>
<div>Bytesear要在比特镇实施Wifi搭建计划，他要让Wifi覆盖到比特镇的每一条道路。</div>
<div>Bytesear可以安置无限多个Wifi发射器，但是只能安置在树上的节点上，一个房子可以安置多个Wifi发射器。</div>
<div>对于一条道路(a,b)，如果它满足以下两个条件之中的至少一个，那么这条边将被Wifi覆盖：</div>
<div>1.a点放置了Wifi发射器或者和b点放置了Wifi发射器。</div>
<div>2.与a点或b点直接相邻的点中，至少放置了两个Wifi发射器。</div>
<div>请帮助Bytesear规划一个最优的放置方案，使得Wifi覆盖到比特镇的每一条道路，且放置的Wifi发射器总数尽可能少。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数n(2&lt;=n&lt;=200000)，表示房子的总数。</div>
<div>接下来n-1行，每行两个正整数a,b(1&lt;=a,b&lt;=n)，表示a点和b点之间有一条边。</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，即最少的Wifi发射器总数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 2<br/>
2 3<br/>
4 3<br/>
5 4<br/>
6 3<br/>
7 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><div>在3号点放置两个Wifi发射器。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

