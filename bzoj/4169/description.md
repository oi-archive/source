
# Description

<div class="content"><div>RHL有一天看到lmc在玩一个游戏。</div>
<div>&#34;愚蠢的人类哟，what are you doing&#34;，RHL说。</div>
<div>&#34;我在玩一个游戏。现在这里有一个有n个结点的有根树，其中有m个叶子结点。这m个叶子从1到m分别被给予了一个</div>
<div>号码，每个叶子的号码都是独一无二的。一开始根节点有一个棋子，两个玩家每次行动将棋子移动到当前节点的一</div>
<div>个儿子节点。当棋子被移动到某个叶节点的时候游戏结束，这个叶节点的号码即为该局游戏的result。先手的玩家</div>
<div>要最大化result，后手的玩家要最小化这个result。&#34;</div>
<div>&#34;你不先问一下我是谁吗 = =&#34;</div>
<div>&#34;那么，who are you&#34;</div>
<div>&#34;我是这个世界的创造者，维护者和毁灭者，整个宇宙的主宰，无所不知，无所不能的，三个字母都大写的RHL。&#34;</div>
<div>&#34;既然你这么厉害，那你一定知道，在两个玩家都无限聪明的情况下，在树的形态已知的情况下，在叶子的编号可</div>
<div>以任意安排的情况下，游戏的result最大是多少咯。&#34;</div>
<div></div></div>

# Input

<div class="content"><div>输入数据第一行有一个正整数n，表示结点的数量。n&lt;=200000</div>
<div>接下来n-1行，每行有两个正整数u和v，表示的父亲节点是u。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行2个非负整数，分别表示result的最大值和最小值。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 2<br/>
【样例解释】<br/>
有3,4,5三个叶子。若令3号叶子的编号是3，则先手可以移到3号结点，故result最大是3。若3号叶子的编号是2，<br/>
则先手可以移到3号结点，故result最小是2.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

