
# Description

<div class="content"><div>烟花表演是最引人注目的节日活动之一。在表演中，所有的烟花必须同时爆炸。为了确保安</div>
<div>全，烟花被安置在远离开关的位置上，通过一些导火索与开关相连。导火索的连接方式形成</div>
<div>一棵树，烟花是树叶，如[图1]所示。火花从开关出发，沿导火索移动。每当火花抵达一个分</div>
<div>叉点时，它会扩散到与之相连的所有导火索，继续燃烧。导火索燃烧的速度是一个固定常</div>
<div>数。[图1]展示了六枚烟花{E1,E2...E6 }的连线布局，以及每根导火索的长度。图中还标</div>
<div>注了当在时刻 从开关点燃火花时，每一发烟花的爆炸时间。</div>
<div><img src="/source/bzoj/4585/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS8xMTEucG5n.png" width="301" height="306" alt=""/></div>
<div>Hyunmin为烟花表演设计了导火索的连线布局。不幸的是，在他设计的布局中，烟花不一定</div>
<div>同时爆炸。我们希望修改一些导火索的长度，让所有烟花在同一时刻爆炸。例如，为了让[图</div>
<div>1]中的所有烟花在时刻 13爆炸，我们可以像[图2]中左边那样调整导火索长度。类似地，为</div>
<div>了让[图1]中的所有烟花在时刻 14爆炸，我们可以像[图2]中右边那样调整长度。</div>
<div><img src="/source/bzoj/4585/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS8yMjIucG5n.png" width="584" height="349" alt=""/></div>
<div>修改导火索长度的代价等于修改前后长度之差的绝对值。例如，将[图1]中布局修改为[图2]</div>
<div>左边布局的总代价为6 ，而将[图1]中布局修改为[图2]右边布局的总代价为 5.</div>
<div>导火索的长度可以被减为0 ，同时保持连通性不变。</div>
<div>给定一个导火索的连线布局，你需要编写一个程序，去调整导火索长度，让所有的烟花在同</div>
<div>一时刻爆炸，并使得代价最小。</div>
<div></div></div>

# Input

<div class="content"><p> 所有的输入均为正整数。令 N代表分叉点的数量， M代表烟花的数量。分叉点从1 到N 编</p>
<div>号，编号为1 的分叉点是开关。烟花从N+1 到 N+M编号。1&lt;=N+M&lt;=300,000</div>
<div>输入格式如下：</div>
<div>N M</div>
<div>P<sub>2</sub> C<sub>2</sub></div>
<div>P<sub>3</sub> C<sub>3</sub></div>
<div>...</div>
<div>P<sub>n</sub> C<sub>n</sub></div>
<div>P<sub>N+1</sub> C<sub>N+1</sub></div>
<div>...</div>
<div>P<sub>N+m</sub> C<sub>N+M</sub></div>
<div>其中Pi 满足 1&lt;=Pi&lt;i，代表和分叉点或烟花i 相连的分叉点。 Ci代表连接它们的导火索长</div>
<div>度( 1&lt;=Ci&lt;=10^9)。除开关外，每个分叉点和多于1 条导火索相连，而每发烟花恰好与 1条导</div>
<div>火索相连。</div></div>

# Output

<div class="content"><p> 输出调整导火索长度，让所有烟花同时爆炸，所需要的最小代价</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
1 5<br/>
2 5<br/>
2 8<br/>
3 3<br/>
3 2<br/>
3 3<br/>
2 9<br/>
4 4<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

