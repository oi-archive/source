
# Description

<div class="content"><div>RHL最近迷上一个小游戏：Flip it。游戏的规则很简单，在一个N*M的格子上，有一些格子是黑色，有一些是白色</div>
<div>。每选择一个格子按一次，格子以及周围边相邻的格子都会翻转颜色（边相邻指至少与该格子有一条公共边的格子</div>
<div>），黑变白，白变黑。RHL希望把所有格子都变成白色的。不幸的是，有一些格子坏掉了，无法被按下。这时，它</div>
<div>可以完成游戏吗？</div></div>

# Input

<div class="content"><div>第一行一个整数T，表示T组数据。</div>
<div>每组数据开始于三个整数n,m,k，分别表示格子的高度和宽度、坏掉格子的个数。接下来的n行，每行一个长度m的</div>
<div>字符串，表示格子状态为&#39;B&#39;或&#39;W&#39;。最后k行，每行两个整数Xi,Yi(1≤Xi≤n,1≤Yi≤m)，表示坏掉的格子。</div>
<div>n,m,k&lt;=256,T&lt;=10</div></div>

# Output

<div class="content"><div>对于每组数据，先输出一行Case #i: (1≤i≤T)</div>
<div>如果可以成功，输出YES，否则输出NO。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 3 0<br/>
WBW<br/>
BBB<br/>
WBW<br/>
3 3 2<br/>
WBW<br/>
BBB<br/>
WBW<br/>
2 2<br/>
3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1:<br/>
YES<br/>
Case #2:<br/>
NO</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

