
# Description

<div class="content"><div>ls和他的妹子sl经常在一个有向图上玩游戏以秀恩爱，允许自环。游戏方式是将棋子放在某一个点，然后每轮可以</div>
<div>将棋子移到它能到达的棋子上，如果某个人不能操作了，则判负。然而规则并没有那么简单，由于sl真是太喜欢ls</div>
<div>了，她很希望ls能多陪陪她，因此如果她有两种决策，一种能让她必胜，另一种能让这个游戏永远持续下去，她会</div>
<div>选择后者，否则如果她不能让这个游戏永远持续下去，她会选择让她赢的决策。反之由于ls十分忙碌，有很多工作</div>
<div>要做，不希望在这个游戏上浪费太多时间，因此如果ls有两种决策，一种会让他必败，一种则会让这个游戏永远持</div>
<div>续下去，他会选择前者，即使他会输给他的妹子，当然，如果他可以不让这个游戏永远持续下去，他还是希望赢的</div>
<div>。ls绝顶聪明，那么他的妹子sl也不会差到哪去，所以两人均采取最优的决策。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n(1&lt;=n&lt;=100000),m(1&lt;=m&lt;=200000)，表示有n个点m条单向边。</div>
<div>之后m行每行两个数u,v，表示有一条u到v的单向边。</div>
<p></p></div>

# Output

<div class="content"><div>两行，第一行输出一个字符串包含n个字符，第i个字符表示sl先手且棋子初始放在第i个点，游戏的结局状况</div>
<div>第二行同样一个字符串包含n个字符，第i个字符表示ls先手且棋子初始放在第i个点，游戏的结局状况。</div>
<div>字符一共三种：&#34;W&#34;表示先手必胜，&#34;L&#34;表示先手必败，&#34;D&#34;则表示游戏将永远持续下去。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 7<br/>
1 2<br/>
2 1<br/>
2 3<br/>
1 4<br/>
4 1<br/>
4 5<br/>
5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">WDLDWL<br/>
DWLLWL</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

