
# Description

<div class="content"><div>题目简述：树版[k取方格数]</div>
<div>众所周知，桂木桂马是攻略之神，开启攻略之神模式后，他可以同时攻略k部游戏。今天他得到了一款新游戏《XX</div>
<div>半岛》，这款游戏有n个场景(scene)，某些场景可以通过不同的选择支到达其他场景。所有场景和选择支构成树状</div>
<div>结构：开始游戏时在根节点（共通线），叶子节点为结局。每个场景有一个价值，现在桂马开启攻略之神模式，同</div>
<div>时攻略k次该游戏，问他观赏到的场景的价值和最大是多少（同一场景观看多次是不能重复得到价值的）</div>
<div>“为什么你还没玩就知道每个场景的价值呢？”</div>
<div>“我已经看到结局了。”</div></div>

# Input

<div class="content"><div>第一行两个正整数n,k</div>
<div>第二行n个正整数，表示每个场景的价值</div>
<div>以下n-1行,每行2个整数a,b，表示a场景有个选择支通向b场景（即a是b的父亲）</div>
<div>保证场景1为根节点</div>
<div>n&lt;=200000，1&lt;=场景价值&lt;=2^31-1</div></div>

# Output

<div class="content"><div>
<div>输出一个整数表示答案</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
4 3 2 1 1<br/>
1 2<br/>
1 5<br/>
2 3<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

