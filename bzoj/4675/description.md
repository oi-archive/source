
# Description

<div class="content"><div>桑尼、露娜和斯塔在玩点对游戏，这个游戏在一棵节点数为n的树上进行。</div>
<div>桑尼、露娜和斯塔三人轮流从树上所有未被占有的节点中选取一点，归为己有，</div>
<div>轮流顺序为桑尼、露娜、斯塔、桑尼、露娜……。该选取过程直到树上所有点都</div>
<div>被选取后结束。</div>
<div>选完点后便可计算每人的得分。点对游戏中有m个幸运数，在某人占据的节</div>
<div>点中，每有一对点的距离为某个幸运数，就得到一分。（树上两点之间的距离定</div>
<div>义为两点之间的简单路径的边数）</div>
<div>你的任务是，假设桑尼、露娜和斯塔每次选取时，都是从未被占有的节点中</div>
<div>等概率选取一点，计算每人的期望得分。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n、m，分别表示树的节点数和幸运数的数目。</div>
<div>第二行m个互异正整数，表示m个幸运数。</div>
<div>以下n-1行，每行两个整数u、v，表示节点u和节点v之间有边。节点从1</div>
<div>到n编号。</div>
<div>3 &lt;= n &lt;= 50000， m &lt;= 10，幸运数大小 &lt;= n</div>
<p></p></div>

# Output

<div class="content"><div>三行实数，分别表示桑尼、露娜和斯塔的期望得分，保留两位小数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
1 3<br/>
1 2<br/>
1 5<br/>
2 3<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.60<br/>
0.60<br/>
0.00<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

