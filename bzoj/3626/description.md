
# Description

<div class="content"><p><span style="font-size: medium">给出一个n个节点的有根树（编号为0到n-1，根节点为0）。一个点的深度定义为这个节点到根的距离+1。<br/>
设dep[i]表示点i的深度，LCA(i,j)表示i与j的最近公共祖先。<br/>
有q次询问，每次询问给出l r z，求sigma_{l&lt;=i&lt;=r}dep[LCA(i,z)]。<br/>
（即，求在[l,r]区间内的每个节点i与z的最近公共祖先的深度之和）</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行2个整数n q。<br/>
接下来n-1行，分别表示点1到点n-1的父节点编号。<br/>
接下来q行，每行3个整数l r z。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出q行，每行表示一个询问的答案。<span style="widows: 2; text-transform: none; text-indent: 0px; display: inline !important; font: 14px/23px Arial; white-space: normal; orphans: 2; float: none; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px">每个答案对201314取模输出</span></span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
0<br/>
0<br/>
1<br/>
1<br/>
1 4 3<br/>
1 4 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
5<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">共5组数据，n与q的规模分别为10000,20000,30000,40000,50000。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=数据已加强 by saffah

">数据已加强 by saffah<br/>
<br/>
</a></p></div>

