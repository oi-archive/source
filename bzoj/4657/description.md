
# Description

<div class="content"><div>Nick最近在玩一款很好玩的游戏，游戏规则是这样的：</div>
<div>有一个n*m的地图，地图上的每一个位置要么是空地，要么是炮塔，要么是一些BETA狗，Nick需</div>
<div>要操纵炮塔攻击BETA狗们。</div>
<div>攻击方法是：对于每个炮塔，游戏系统已经给出它可以瞄准的方向(上下左右其中一个），Nick需要</div>
<div>选择它的攻击位置，每一个炮塔只能够攻击一个位置，炮塔只能够向着它的瞄准方向上的某个位置发</div>
<div>动攻击，当然炮塔也可以不进行攻击。炮塔威力强大，它可以且仅可以消灭目标位置上所有的BETA狗。</div>
<div>出于安全考虑，游戏系统已经保证不存在一个炮塔能够瞄准另外一个炮塔，即对于任意一个炮</div>
<div>塔，它所有可能的攻击位置上不存在另外一个炮塔。而且，如果把炮塔的起点和终点称为炮弹的运行</div>
<div>轨迹，那么系统不允许两条轨迹相交f包括起点和终点）。</div>
<div>现在，选定目标位置以后，每一个炮塔同时开炮，你要告诉Nick，他最多可以干掉多少BETA狗。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个正整数n，m，表示地图的规模。</div>
<div>接下来礼行，每行m个整数，0表示空地，-1，-2，一3，-4分别表示瞄准上下左右的炮塔，若为正整</div>
<div>数p，则表示该位置有p个BETA狗。</div>
<div>n，m &lt;= 50，每个位置的BETA狗数量不超过999个，保证不存在任意一个炮塔能够瞄准另外一个炮塔</div>
<div></div>
<div></div></div>

# Output

<div class="content"><div>一个正整数，表示Nick最多可以干掉几个BETA狗</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
0 9<br/>
-4 3<br/>
0 -1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

