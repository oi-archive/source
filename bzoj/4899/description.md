
# Description

<div class="content"><div>通往贤者之塔的路上，有许多的危机。</div>
<div>我们可以把这个地形看做是一颗树，根节点编号为1，目标节点编号为n，其中1-n的简单路径上，编号依次递增，</div>
<div>在[1,n]中，一共有n个节点。我们把编号在[1,n]的叫做正确节点，[n+1,m]的叫做错误节点。一个叶子，如果是正</div>
<div>确节点则为正确叶子，否则称为错误叶子。莎缇拉要帮助昴到达贤者之塔，因此现在面临着存档位置设定的问题。</div>
<div>为了让昴成长为英雄，因此一共只有p次存档的机会，其中1和n必须存档。被莎缇拉设置为要存档的节点称为存档</div>
<div>位置。当然不能让昴陷入死循环，所以存档只能在正确节点上进行，而且同一个节点不能存多次档。因为通往贤者</div>
<div>之塔的路上有影响的瘴气，因此莎缇拉假设昴每次位于树上一个节点时，都会等概率选择一个儿子走下去。每当走</div>
<div>到一个错误叶子时，再走一步就会读档。具体的，每次昴到达一个新的存档位置，存档点便会更新为这个位置（假</div>
<div>如现在的存档点是i，现在走到了一个存档位置j&gt;i，那么存档点便会更新为j）。读档的意思就是回到当前存档点</div>
<div>。初始昴位于1，当昴走到正确节点n时，便结束了路程。莎缇拉想知道，最优情况下，昴结束路程的期望步数是多</div>
<div>少？</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数T表示数据组数。</div>
<div>接下来每组数据，首先读入三个正整数n,m,p。</div>
<div>接下来m-n行，描述树上所有的非正确边（正确边即连接两个正确节点的边）</div>
<div>用两个正整数j，k表示j与k之间有一条连边，j和k可以均为错误节点，也可以一个为正确节点另一个为错误节点。</div>
<div>数据保证j是k的父亲。</div>
<div>50&lt;=p&lt;=n&lt;=700，m&lt;=1500，T&lt;=5。</div>
<div>数据保证每个正确节点均有至少2个儿子，至多3个儿子。</div>
<p></p></div>

# Output

<div class="content"><div>T行每行一个实数表示每组数据的答案。请保留四位小数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3 7 2<br/>
1 4<br/>
2 5<br/>
3 6<br/>
3 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">9.0000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By WerKeyTom_FTD">By WerKeyTom_FTD</a></p></div>

