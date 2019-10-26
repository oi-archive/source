
# Description

<div class="content"><div>风见幽香非常喜欢玩一个叫做 osu!的游戏，其中她最喜欢玩的模式就是接水果。</div>
<div>由于她已经DT FC 了The big black,  她觉得这个游戏太简单了，于是发明了一个更</div>
<div>加难的版本。首先有一个地图，是一棵由 n 个顶点、n-1 条边组成的树（例如图 1</div>
<div>给出的树包含 8 个顶点、7 条边）。这颗树上有 P 个盘子，每个盘子实际上是一条</div>
<div>路径（例如图 1 中顶点 6 到顶点 8 的路径），并且每个盘子还有一个权值。第 i 个</div>
<div>盘子就是顶点a_i到顶点b_i的路径(由于是树，所以从a_i到b_i的路径是唯一的)，</div>
<div>权值为c_i。接下来依次会有Q个水果掉下来，每个水果本质上也是一条路径，第</div>
<div>i 个水果是从顶点 u_i 到顶点v_i 的路径。幽香每次需要选择一个盘子去接当前的水</div>
<div>果：一个盘子能接住一个水果，当且仅当盘子的路径是水果的路径的子路径（例如</div>
<div>图1中从 3到7 的路径是从1到8的路径的子路径）。这里规定:从a 到b的路径与</div>
<div>从b到 a的路径是同一条路径。当然为了提高难度，对于第 i 个水果，你需要选择</div>
<div>能接住它的所有盘子中，权值第 k_i 小的那个盘子，每个盘子可重复使用（没有使用次数</div>
<div>的上限：一个盘子接完一个水果后，后面还可继续接其他水果，只要它是水</div>
<div>果路径的子路径）。幽香认为这个游戏很难，你能轻松解决给她看吗？ </div>
<div><img src="/source/bzoj/4009/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC9hYWFhLlBORw==.PNG" width="395" height="212" alt=""/></div>
<div></div></div>

# Input

<div class="content"><p>第一行三个数 n和P 和Q，表示树的大小和盘子的个数和水果的个数。 </p>
<div>
<div>接下来n-1 行，每行两个数 a、b，表示树上的a和b 之间有一条边。树中顶点</div>
<div>按1到 n标号。 接下来 P 行，每行三个数 a、b、c，表示路径为 a 到 b、权值为 c 的盘子，其</div>
<div>中0≤c≤10^9，a不等于b。 </div>
<div>接下来Q行，每行三个数 u、v、k，表示路径为 u到 v的水果，其中 u不等于v，你需要选择第 k小的盘子，</div>
<div>第k 小一定存在。 </div>
<div></div>
</div></div>

# Output

<div class="content"><p> 对于每个果子，输出一行表示选择的盘子的权值。 </p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10 10 <br/>
1 2 <br/>
2 3 <br/>
3 4 <br/>
4 5 <br/>
5 6 <br/>
6 7 <br/>
7 8 <br/>
8 9 <br/>
9 10 <br/>
3 2 217394434 <br/>
10 7 13022269 <br/>
6 7 283254485 <br/>
6 8 333042360 <br/>
4 6 442139372 <br/>
8 3 225045590 <br/>
10 4 922205209 <br/>
10 8 808296330 <br/>
9 2 486331361 <br/>
4 9 551176338 <br/>
1 8 5 <br/>
3 8 3 <br/>
3 8 4 <br/>
1 8 3 <br/>
4 8 1 <br/>
2 3 1 <br/>
2 3 1 <br/>
2 3 1 <br/>
2 4 1 <br/>
1 4 1 </span></div>

# Sample Output

<div class="content"><span class="sampledata">442139372 <br/>
333042360 <br/>
442139372 <br/>
283254485 <br/>
283254485 <br/>
217394434 <br/>
217394434 <br/>
217394434 <br/>
217394434 <br/>
217394434 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p>N,P,Q&lt;=40000。 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

