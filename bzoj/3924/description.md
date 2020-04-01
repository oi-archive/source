
# Description

<div class="content"><p> 傲娇少女幽香正在玩一个非常有趣的战略类游戏，本来这个游戏的地图其实还不算太大，幽香还能管得过来，但是不知道为什么现在的网游厂商把游戏的地图越做越大，以至于幽香一眼根本看不过来，更别说和别人打仗了。 在打仗之前，幽香现在面临一个非常基本的管理问题需要解决。 整个地图是一个树结构，一共有n块空地，这些空地被n-1条带权边连接起来，使得每两个点之间有一条唯一的路径将它们连接起来。在游戏中，幽香可能在空地上增加或者减少一些军队。同时，幽香可以在一个空地上放置一个补给站。 如果补给站在点u上，并且空地v上有dv个单位的军队，那么幽香每天就要花费dv×dist(u,v)的金钱来补给这些军队。由于幽香需要补给所有的军队，因此幽香总共就要花费为Sigma(Dv*dist(u，v),其中1&lt;=V&lt;=N)的代价。其中dist(u,v)表示u个v在树上的距离（唯一路径的权和）。 因为游戏的规定，幽香只能选择一个空地作为补给站。在游戏的过程中，幽香可能会在某些空地上制造一些军队，也可能会减少某些空地上的军队，进行了这样的操作以后，出于经济上的考虑，幽香往往可以移动他的补给站从而省一些钱。但是由于这个游戏的地图是在太大了，幽香无法轻易的进行最优的安排，你能帮帮她吗？ 你可以假定一开始所有空地上都没有军队。</p>
<p>PDF版试题:<a href="/JudgeOnline/upload/201708/zjoi2015d1.pdf">JudgeOnline/upload/201708/zjoi2015d1.pdf</a></p></div>

# Input

<div class="content"><div>
<div>第一行两个数n和Q分别表示树的点数和幽香操作的个数，其中点从1到n标号。 </div>
<div>接下来n-1行，每行三个正整数a,b,c，表示a和b之间有一条边权为c的边。 </div>
<div>接下来Q行，每行两个数u,e，表示幽香在点u上放了e单位个军队</div>
<div>（如果e&lt;0，就相当于是幽香在u上减少了|e|单位个军队，说白了就是du←du+e）。</div>
<div>数据保证任何时刻每个点上的军队数量都是非负的。 </div>
<div>1&lt;=c&lt;=1000, 0&lt;=|e|&lt;=1000, n&lt;=10^5, Q&lt;=10^5</div>
<div>对于所有数据，这个树上所有点的度数都不超过20</div>
<div>N,Q&gt;=1</div>
</div>
<div>
<div></div>
</div></div>

# Output

<div class="content"><p> 对于幽香的每个操作，输出操作完成以后，每天的最小花费，也即如果幽香选择最优的补给点进行补给时的花费。 </p></div>

# Sample Input

<div class="content"><span class="sampledata">10 5<br/>
1 2 1<br/>
2 3 1<br/>
2 4 1<br/>
1 5 1<br/>
2 6 1<br/>
2 7 1 <br/>
5 8 1<br/>
7 9 1<br/>
1 10 1<br/>
3 1<br/>
2 1<br/>
8 1<br/>
3 1<br/>
4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
4<br/>
5<br/>
6</span></div>

# Hint

<div class="content"><p></p><div></div><br/>
<div></div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

