
# Description

<div class="content"><p><span style="font-size: medium">描述<br/>
到海边了呢......<br/>
如果没有那次选择,现在是不是会好些呢......<br/>
都过去了。<br/>
仰望着星空,迎面吹过一阵阵海风,倚靠着护栏,Fine 在海边静静地伫立着,在一个个无际的长夜后,Fine 终于放下了往事的痛楚,得到了治愈。<br/>
但是作为 Fine 的另一重人格的 Falsita 就没那么幸运了。她仍然被各种繁忙的事务困扰着。<br/>
虽然同在一副躯体中,Fine 与 Falsita 的精神世界却相差甚远,Fine 可以轻易地构造出幻梦时,Falsita 却只能停留在现实的痛楚中。<br/>
但是为了生活需要,她们还是需要经常达成共识。<br/>
让我们形式化的描述一下吧。<br/>
她们所在的精神世界是一棵以 1 号节点为根的树,每个树上的节点 u 都有一个权值Wu,她们每个人分别都在一个节点上,达成共识的方法就是两个人都到达一个共识节点(即到达它们的最近公共祖先)。<br/>
一个点 u 与另外一个点 v 之间想要达到共识需要花费的代价为Wu+Wv。<br/>
有时两人的精神有所触动时,有时点的权值会改变成某个数,有时以某个点的子树中的所有点的权值会加上某个数。<br/>
Falsita 和 Fine 经常需要达成共识,每一次询问,已知达成的共识节点,求她们花费的期望代价。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入共 m + 3 行。<br/>
第一行两个整数 n, m ,表示节点个数和操作数。<br/>
第二行 n - 1 个整数Pi,表示节点 i ( i = 2 . . . n ) 的父亲节点的编号。<br/>
第三行 n 个整数Wi。<br/>
接下来 m 行,每行表示一个操作。<br/>
1. S u delta 表示将节点 u 的权值加上 delta 。<br/>
2. M u delta 表示将以节点 u 为根的子树中的所有节点的权值加上 delta。<br/>
3. Q u 表示询问共识节点为 u 时的答案。<br/>
询问保证 u 不是叶子节点。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每组询问,输出答案,答案精确到小数点后 6 位。<br/>
你的程序输出的答案需要与标准答案之差不超过10^(-5)。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
1 2 2 <br/>
0 -6 3 0 <br/>
S 2 -5<br/>
M 3 8<br/>
S 1 -1<br/>
M 4 7<br/>
M 3 2<br/>
Q 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.000000<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">前5个操作后，四个节点的权值分别为-1,-11,13,7。最近公共祖先为1的点对有(1,2),(1,3),(1,4)，权值和分别为-12,12,6，故答案为(-12+12+6)/3=2。<br/><br/>
<br/><br/>
<br/><br/>
对于 100% 的数据,1 ≤ n, m ≤ 300000, 0≤ |delta|, |Wi|≤ 20000。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Shinrein祭 #1">Shinrein祭 #1</a></p></div>

