
# Description

<div class="content"><div>石子游戏是大家都很喜欢玩的一类游戏，这类游戏通常与石子的移动和取</div>
<div>舍有关，往往可以让人在游戏中获得不少的乐趣。</div>
<div>有一类树上石子游戏的规则是这样的：在一棵有根树上，每个节点都有着</div>
<div>一定数目的石子，两个玩家轮流进行游戏。每次，每个玩家可以把不超过 m 个</div>
<div>的石子移动到它的父亲上。显然，根节点没有父亲，故每个石子一旦移动到根</div>
<div>节点便无法再次移动。问题是以某个节点为根的子树进行这样的游戏，是否存</div>
<div>在先手必胜策略。</div>
<div>为了增加这个游戏的难度，我们对这个游戏进行一些小小的修改。现在，</div>
<div>我们的这棵树可能会长出新的节点。同时，每个节点上的石子数目可能会变化。</div>
<div>请问，以某个节点为根的子树进行这样的石子游戏，是否存在先手必胜策略。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个数字 n 和 m，表示初始时有 n 个节点，</div>
<div>每次移动不能超过 m 个。</div>
<div>第二行 n 个正整数 a1,a2...an，表示初始时候的石子数量，其中 1 号节</div>
<div>点为根节点。</div>
<div>接下来 n   1 行，每行两个整数 u 和 v，表示有一条从 u 到 v 的边。</div>
<div>接下来一行一个数 t,表示操作的数目。</div>
<div>接下来 t 行，每行代表一个操作，每行的第一个数字代表操作类型，其中：</div>
<div>若为 1，后跟一个数字 v，表示询问在 v 的子树中做游戏先手是否必胜。</div>
<div>若为 2，后跟两个数字 x， y 表示将节点 x 的石子数修改为 y。</div>
<div>若为 3，后跟三个数字 u， v， x，表示为 u 节点添加一个儿子 v，初始石</div>
<div>子数为 x。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每一个询问，若先手必胜输出“Yes”，否则输出“No”。</div>
<div>注，数据进行了强制在线处理，对于每一个操作，除类型名外，都需要异</div>
<div>或之前回答为“Yes“的数目。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1000<br/>
0 0<br/>
1 2<br/>
1<br/>
1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">No</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据， n,t &lt;= 50000。</div><br/>
<div>同时，保证任何时刻树中节点数目和编号都不会超过 100000。</div><br/>
<div>其余数据的范围皆在int范围内。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

