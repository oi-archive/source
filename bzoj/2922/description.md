
# Description

<div class="content"><p><span style="font-size: medium"><br/>
追逐游戏是一个双人游戏，假设有玩家A和B。一个棋盘包含由1到n编号的格子。对于一对编号不同的格子，会给定它们之间是否相连。每个玩家控制一个棋子。开始的时候，每个玩家的棋子会放在某个特定的不同的格子。在一回合中，玩家可以移开它的棋子，移到一个相邻的格子。</span></p>
<p><span style="font-size: medium">一个棋盘有下面属性：</span></p>
<p><span style="font-size: medium">* 不存在三角形连接的格子<br/>
* 每个格子都可以被走到</span></p>
<p><span style="font-size: medium">一次游戏由若干回合组成。在每个回合，每个玩家只能动一步。每回合A先开始动。</span></p>
<p><span style="font-size: medium">当两个棋子站在一起的时候，我们说A被B吃掉了。给定棋子的初始位置，假定AB都选用最佳决策，判断B是否必胜。如果是的话，需要多少回合。</span></p>
<p><span style="font-size: medium">例如：</span></p>
<p><span style="font-size: medium">&lt;img src=&#34;</span><a href="http://main.edu.pl/en/images/OI5/gon.gif"><span style="font-size: medium">http://main.edu.pl/en/images/OI5/gon.gif</span></a><span style="font-size: medium">&#34; alt=&#34;example&#34; /&gt;</span></p>
<p><span style="font-size: medium">上图的棋盘，用边连起来的是相邻的格子。如果开始的时候，A和B的棋子分别站在9和4的位置，那么在第3轮B可以吃掉A。如果A和B分别在8和4，那么B就无法吃掉A。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行，4个整数：格子数量n(2&lt;=n&lt;=3000)，边数m(n-1&lt;=m&lt;=15000)，A和B的初始位置a b(a &lt; b)<br/>
下面m行：(u, v) 描述一对相邻的格子</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">如果B能吃掉A的话，输出最少需要的回合数。否则输出&#34;NIE&#34;</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 11 9 4<br/>
1 2<br/>
3 2<br/>
1 4<br/>
4 7<br/>
7 5<br/>
5 1<br/>
6 9<br/>
8 5<br/>
9 8<br/>
5 3<br/>
4 8<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

