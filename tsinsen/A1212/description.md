<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出一棵有根树。树有n个结点，被分别标记成1到n的整数，1号结点为根结点。第i(1≤i≤n)个结点的权值为Wi。对于结点i，它有Ti个孩子，从左到右依次为Pi<sub>1</sub>，<i>Pi<sub>2</sub></i>，…，<i>Pi<sub>Ti</sub></i>。特别地，若i号结点是叶结点，则T<sub>i</sub>=0。<br/>
　　我们对树进行深度优先搜索（DFS），每个点必须按从左到右的顺序访问每个孩子，形成一个DFS序列，记作Seq{<i>Seq<sub>1</sub></i>,<i>Seq<sub>2</sub></i>,…,<i>Seq<sub>n</sub></i>}。对于两个叶结点a、b，我们说它们是相邻的，当且仅当不存在另外的叶结点c，在DFS序列中c在a、b之间。换个方式讲，对于叶结点a、b、c，记Seq<sub>i</sub>=<i>a</i>,<i>Seq<sub>j</sub></i>=b(<i>i</i>&lt;<i>j</i>) ，不存在<i>Seq<sub>k</sub></i>=<i>c</i>，使得<i>i</i>&lt;<i>k</i>&lt;<i>j</i>。<br/>
　　每对相邻的叶结点（a,b），都存在一个影响值。影响值定义为a到b的路径上（不包含a、b的结点）的最大点权值。<br/>
　　定义一棵树的价值等于这棵树所有叶结点的权值之和减去每对相邻叶结点的影响值。<br/>
　　当然，要是让你算这棵树的价值就太简单了。你的目标是对树进行一些剪枝，使树的价值最大。剪枝的方式为：如果一个结点的孩子都是叶结点，就可以将它所有的孩子剪去。</div>
# 输入格式

<div class="pdcont">　　第1行：n；<br/>
　　第2..n+1行：第i+1行为W<sub>i</sub>，<i>T<sub>i</sub></i>，<i>Pi<sub>1</sub></i>，<i>Pi<sub>2</sub></i>，…，<i>Pi<sub>Ti</sub></i>。</div>
# 输出格式

<div class="pdcont">　　第1行：这棵树修改后的最大价值。</div>
# 样例输入

<div class="pddata">5<br/>
1 2 2 3<br/>
2 0<br/>
2 0</div>
# 样例输出

<div class="pddata">3</div>
# 样例输入

<div class="pddata">8<br/>
4 2 2 3<br/>
2 3 4 5 6<br/>
3 2 7 8<br/>
5 0<br/>
4 0<br/>
2 0<br/>
1 0<br/>
1 0</div>
# 样例输出

<div class="pddata">6</div>
# 数据规模和约定

<div class="pdcont">　　对于20%的数据，n≤20；<br/>
　　对于60%的数据，n≤2000；<br/>
　　对于100%的数据，n≤100000，0&lt;<i>W<sub>i</sub></i>≤10000。</div>

</div>