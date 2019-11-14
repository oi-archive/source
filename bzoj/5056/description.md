
# Description

<div class="content"><div>小Van的CP最喜欢玩与OI有关的游戏啦~小Van为了讨好她，于是冥思苦想，终于创造了一个新游戏。</div>
<div>下面是小Van的OI游戏规则：</div>
<div>给定一个无向连通图，有N个节点，编号为0~N-1。图里的每一条边都有一个正整数权值，边权在1~9之间。</div>
<div>要求从图里删掉某些边（有可能0条），使得剩下的图满足以下两个条件：</div>
<div>1） 剩下的图是一棵树，有N-1条边。</div>
<div>2） 对于所有v (0 &lt; v &lt; N)，0到v的最短路（也就是树中唯一路径长度）和原图中的最短路长度相同。</div>
<div>最终要报出有多少种不同的删法可以满足上述条件。（两种删法不同当且仅当存在两个点，</div>
<div>一种删法删完之后这两个点之间存在边而另外一种删法不存在。）</div>
<div>由于答案有可能非常大，良心的小Van只需要答案膜1,000,000,007的结果。</div>
<div>后记： 然而这游戏太高难度了，小Van的CP做不出来因此很不开心！</div>
<div>她认为小Van在故意刁难她，于是她与小Van分手了。。。</div>
<div>不过对于精通OI的你来说，这不过是小菜一碟啦！</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数N，代表原图结点。</div>
<div>接下来N行，每行N个字符，描绘了一个邻接矩阵。邻接矩阵中，</div>
<div>如果某一个元素为0，代表这两个点之间不存在边，</div>
<div>并且保证第i行第i列的元素为0，第i行第j列的元素(i≠j)等于第j行第i列的元素。</div>
<div>2≤N≤50</div>
<p></p></div>

# Output

<div class="content"><div>一行一个整数，代表删法总方案数膜1,000,000,007的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Input1<br/>
2 <br/>
01 <br/>
10 <br/>
<br/>
<br/>
Input2<br/>
4 <br/>
0123 <br/>
1012 <br/>
2101 <br/>
3210 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Output1<br/>
1<br/>
Output2<br/>
6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

