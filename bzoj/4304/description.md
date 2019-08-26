
# Description

<div class="content"><div>人称不死将军的林登•万，与他的兄弟林登•图两人的足迹踏遍了地球的每一寸土地。他们曾将战火燃遍了世界。即使是lifei888这样的强悍人物也从来没有将他彻底击败。</div>
<div>这一次，林登•万在N个城市做好了暴动的策划。然而，在起事的前一天，将军得知计划已经泄漏，决定更改计划，集中力量掌握一部分城市。</div>
<div>具体来说，有M条单向边连接着这N座城市。对于两座城市A,B，如果它们能够通过单向边直接或间接的互相到达，那么就林登•万可以同时控制A,B两座城市而不至于分散力量，反之则会被lifei888各个击破。</div>
<div>为了扩大成果，将军还组织了人手改建道路。这些人可以在起事前将其中一条有向边改变成双向边（注意只能改建其中一条单向边，另外M-1条单向边保持不变）,现在，将军想要知道他通过改建其中一条单向边最多能控制几座城市，以及被改建的这一条单向边有多少种选择方案。</div>
<p></p></div>

# Input

<div class="content"><div>第一行为两个正整数N,M。</div>
<div>接下来M行每行两个范围在1~N内的正整数x,y，表示有一条从x到y的单向边。</div>
<div>输入保证任意两点的任意方向最多只有一条边直接相连。</div>
<p></p></div>

# Output

<div class="content"><div>输出共三行。</div>
<div>第一行一个正整数，将军最多能控制的城市数量。</div>
<div>第二行一个正整数L，表示有L种改建方案使得将军能控制最多的城市。</div>
<div>第三行L个按递增顺序给出的正整数ki，表示改建输入中的第ki条有向边能使将军能控制最多的城市。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
1 2<br/>
2 3<br/>
1 3<br/>
4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;&lt;br /&gt;
mso-hansi-font-family:&#34;Times New Roman&#34;">对于</span><span lang="EN-US">100%</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&lt;br /&gt;
&#34;Times New Roman&#34;">的数据，</span><span lang="EN-US">N&lt;=<st1:chmetcnv unitname="m" sourcevalue="2000" hasspace="True" negative="False" numbertype="1" tcsc="0" w:st="on">2000 M</st1:chmetcnv>&lt;=N*N</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

