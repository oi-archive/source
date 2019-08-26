
# Description

<div class="content"><div>小Y家里有一个大森林，里面有n棵树，编号从1到n。一开始这些树都只是树苗，只有一个节点，标号为1。这些树</div>
<div>都有一个特殊的节点，我们称之为生长节点，这些节点有生长出子节点的能力。小Y掌握了一种魔法，能让第l棵树</div>
<div>到第r棵树的生长节点长出一个子节点。同时她还能修改第l棵树到第r棵树的生长节点。她告诉了你她使用魔法的</div>
<div>记录，你能不能管理她家的森林，并且回答她的询问呢？</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行包含 2 个正整数 n,m，共有 n 棵树和 m 个操作。接下来 m 行，每行包含若干非负整数表示一个操作，操</div>
<div>作格式为：</div>
<div>0 l r 表示将第 l 棵树到第 r 棵树的生长节点下面长出一个子节点，子节点的标号为上一个 0 号操作叶子标号</div>
<div>加 1（例如，第一个 0 号操作产生的子节点标号为 2）， l 到 r 之间的树长出的节点标号都相同。保证 1≤l≤</div>
<div>r≤n 。</div>
<div>1 l r x 表示将第 l 棵树到第 r 棵树的生长节点改到标号为 x 的节点。对于 i (l≤i≤r)这棵树，如果标号 x</div>
<div>的点不在其中，那么这个操作对该树不产生影响。保证 1≤l≤r≤n ， x 不超过当前所有树中节点最大的标号。</div>
<div>2 x u v 询问第 x 棵树中节点 u 到节点 v 点的距离，也就是在第 x 棵树中从节点 u 和节点 v 的最短路上边的</div>
<div>数量。保证1≤x≤n，这棵树中节点 u 和节点 v 存在。N&lt;=10^5,M&lt;=2*10^5</div>
</div></div>

# Output

<div class="content"><p>输出包括若干行，按顺序对于每个小Y的询问输出答案</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
0 1 5<br/>
1 2 4 2<br/>
0 1 4<br/>
2 1 1 3<br/>
2 2 1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

