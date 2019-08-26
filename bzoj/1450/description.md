
# Description

<div class="content"><div>Seter和Fotile在一棵N个点的树上玩游戏。这棵树的每个点不是黑色的就是白色的。</div>
<div>他们轮流进行以下操作：</div>
<div>在当前的树上选择一个白色节点；</div>
<div>把1号点到选择节点的路径上所有点涂黑。</div>
<div>Seter或Fotile输掉游戏当且仅当无法操作（没有白色节点）。</div>
<div>Seter用石头剪刀布获得了先手机会，但是他知道Fotile很聪明，会按照最优策略选点</div>
<div>他想知道自己有没有可能赢得游戏，否则他就要掀桌了。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数N表示树的节点数。 1&lt;=n&lt;=100000</div>
<div>第二行包括N个0或1：c1,c2,..cn。</div>
<div>ci=0 表示第i个点一开始是白色的而 ci=1 表示黑色。</div>
<div>接下来N-1行每行两个整数u,v描述整棵树。</div>
<p></p></div>

# Output

<div class="content"><div>如果Seter输定了或者你也不会做，输出-1让他掀桌.</div>
<div>否则按照增序输出所有Seter第一步可以选择的点，使得Seter能获胜。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Input#1:<br/>
8<br/>
1 1 0 1 0 0 1 0<br/>
1 2<br/>
1 3<br/>
2 6<br/>
3 4<br/>
3 5<br/>
5 7<br/>
7 8 <br/>
Input#2:<br/>
20<br/>
1 1 1 0 1 1 1 0 1 0 0 0 1 0 1 0 0 0 0 0<br/>
1 2<br/>
2 3<br/>
2 4<br/>
1 5<br/>
1 6<br/>
5 7<br/>
5 8<br/>
2 9<br/>
8 10<br/>
1 11<br/>
1 12<br/>
9 13<br/>
6 14<br/>
14 15<br/>
7 16<br/>
11 17<br/>
2 18<br/>
7 19<br/>
12 20 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Output#1:<br/>
5<br/>
<br/>
Output#2<br/>
8<br/>
11<br/>
12 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

