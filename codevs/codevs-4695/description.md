<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个很有趣的游戏叫做海盗船。这是一个在9*8的棋盘上进行的游戏，棋盘上的每个格子可能是下面4种状态之一：</p><p>“.”：表示当前格子为空；</p><p>“S”：表示你的船所在的位置；</p><p>“E”：表示敌船所在的位置；</p><p>“#”：表示一座小岛。</p><p>每次你可以将你的船朝周围的8个方向之一移动，但不能停留。在你移动完之后，所有的敌船会朝周围8个位置中和你的船当前位置距离最近的那个格子移动。在这
个过程中，如果某艘敌船碰到了小岛，那么这艘敌船将会沉没。如果两艘敌船同时走到同一个格子中，那么这两艘敌船将会同时沉没，并且其残骸将会在该位置形成
障碍，也就是说如果还有敌船走到这个位置，那么该敌船也会沉没。每艘敌船上都装了烈性炸药，如果你不幸让某艘敌船撞到了你，你就可以和我们敬仰的祖先欢聚
一堂了。</p><p>现在你的任务是通过移动你的船来消灭所有的敌船，当然，在移动过程中，请确保你的船不要撞倒小岛或者敌船的残骸。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数T，表示测试数据组数，以下每组数据包含一个9*8的地图，地图上的符号以及意义如题目所述。相邻的两组数据间用一个空行隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组数据输出一行信息。如果你能够消灭所有的海盗船，那么输出“I&#39;m the king of the Seven Seas!”，否则输出“Oh no! I&#39;m a dead man!”。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>........<br>........<br>........<br>...E....<br>...#S...<br>........<br>........<br>........<br>.......E<br><br>........<br>........<br>.....E..<br>..E#.#..<br>....S...<br>...#.#E.<br>...E....<br>........<br>........</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>I'm the king of the Seven Seas!<br>Oh no! I'm a dead man!</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于100%的数据，1 ≤ T ≤ 100</span>.<br></p>
</div>
</div>