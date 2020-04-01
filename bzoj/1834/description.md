
# Description

<div class="content"><div>给定一张有向图，每条边都有一个容量C和一个扩容费用W。这里扩容费用是指将容量扩大1所需的费用。</div>
<div>求： </div>
<div>1、在不扩容的情况下，1到N的最大流； </div>
<div>2、将1到N的最大流增加K所需的最小扩容费用。</div></div>

# Input

<div class="content"><div>第一行包含三个整数N,M,K，表示有向图的点数、边数以及所需要增加的流量。 </div>
<div>接下来的M行每行包含四个整数u,v,C,W，表示一条从u到v，容量为C，扩容费用为W的边。</div>
<div>N&lt;=1000，M&lt;=5000，K&lt;=10</div></div>

# Output

<div class="content"><p>输出文件一行包含两个整数，分别表示问题1和问题2的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 8 2<br/>
1 2 5 8<br/>
2 5 9 9<br/>
5 1 6 2<br/>
5 1 1 8<br/>
1 2 8 7<br/>
2 5 4 9<br/>
1 2 1 1<br/>
1 4 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">13 19<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

