<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Plants vs. Zombies（PVZ）是最近十分风靡的一款小游戏。Plants（植物）和Zombies（僵尸）是游戏的主角，其中：Plants防守，而Zombies进攻。该款游戏包含多种不同的挑战系列，比如Protect Your Brain、Bowling等等。其中最为经典的，莫过于玩家通过控制Plants来防守Zombies的进攻，或者相反地由玩家通过控制Zombies对Plants发起进攻。</p><p>现在，我们将要考虑的问题是游戏中Zombies对Plants的进攻，请注意，本题中规则与实际游戏有所不同。游戏中有两种角色，Plants和Zombies，每个Plant有一个攻击位置集合，它可以对这些位置进行保护；而Zombie进攻植物的方式是走到植物所在的位置上并将其吃掉。</p><p>游戏的地图可以抽象为一个N行M列的矩阵，行从上到下用0到N-1编号，列从左到右用0到M-1编号；在地图的每个位置上都放有一个Plant，为简单起见，我们把位于第r行第c列的植物记为P<sub>r</sub><sub>，c</sub>。</p><p>Plants分很多种，有攻击类、防守类和经济类等等。为了简单的描述每个Plant，定义Score和Attack如下：</p><table border="1" cellpadding="0" cellspacing="0"><tbody><tr><td valign="top" width="151"><p>Score[P<sub>r</sub><sub>，c</sub>]</p><p> </p></td><td valign="top" width="416"><p>Zombie击溃植物P<sub>r</sub><sub>，c</sub>可获得的能源。若Score[P<sub>r</sub><sub>，c</sub>]为非负整数，则表示击溃植物P<sub>r</sub><sub>，c</sub>可获得能源Score[P<sub>r</sub><sub>，c</sub>]，若为负数表示击溃P<sub>r</sub><sub>，c</sub>需要付出能源-Score[P<sub>r</sub><sub>，c</sub>]。</p></td></tr><tr><td valign="top" width="151"><p>Attack[P<sub>r</sub><sub>，c</sub>]</p></td><td valign="top" width="416"><p>植物P<sub>r</sub><sub>，c</sub>能够对Zombie进行攻击的位置集合。</p></td></tr></tbody></table><p>Zombies必须从地图的右侧进入，且只能沿着水平方向进行移动。Zombies攻击植物的唯一方式就是走到该植物所在的位置并将植物吃掉。因此Zombies的进攻总是从地图的右侧开始。也就是说，对于第r行的进攻，Zombies必须首先攻击P<sub>r</sub><sub>，M-1</sub>；若需要对P<sub>r</sub><sub>，c</sub>（0&lt;=c&lt;M-1）攻击，必须将P<sub>r</sub><sub>，M-1</sub>，P<sub>r</sub><sub>，M-2</sub>，&amp;hellip;，P<sub>r</sub><sub>，c+1</sub>先击溃，并移动到位置（r，c）才可进行攻击。</p><p>在本题的设定中，Plants的攻击力是无穷大的，一旦Zombie进入某个Plant的攻击位置，该Zombie会被瞬间消灭，而该Zombie没有时间进行任何攻击操作。因此，即便Zombie进入了一个Plant所在的位置，但该位置属于其他植物的攻击位置集合，则Zombie会被瞬间消灭而所在位置的植物则安然无恙（在我们的设定中，Plant的攻击位置不包含自身所在位置，否则你就不可能击溃它了）。</p><p>Zombies的目标是对Plants的阵地发起进攻并获得最大的能源收入。每一次，你可以选择一个可进攻的植物进行攻击。本题的目标为，制定一套Zombies的进攻方案，选择进攻哪些植物以及进攻的顺序，从而获得最大的能源收入。</p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中的第一行为两个整数N，M，分别表示地图的行数和列数。</p><p>接下来的N&amp;times;M行，描述了每个位置上植物的信息。其中：第r&amp;times;M+c+1行按照如下格式给出植物P<sub>r</sub><sub>，c</sub>的信息：第一个整数为Score[P<sub>r</sub><sub>，c</sub>]，第二个整数为集合Attack[P<sub>r</sub><sub>，c</sub>]中的位置个数w，接下来为w个位置信息（r'，c'），表示P<sub>r</sub><sub>，c</sub>可以攻击位置第r'行第c'列。</p><p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中仅一行为一个整数，表示可以获得的最大能源收入。</p><p>注意：你也可以选择不进行任何攻击，这样能源收入为0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2</p><p>10 0</p><p>20 0</p><p>-10 0</p><p>-5 1 0 0</p><p>100 1 2 1</p><p>100 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>25</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】</p><p>在样例中，植物P<sub>1</sub><sub>，1</sub>可以攻击位置（0，0），P<sub>2</sub><sub>，0</sub>可以攻击位置（2，1）。</p><p>一个方案为，首先进攻P<sub>1</sub><sub>，1</sub>，P<sub>0</sub><sub>，1</sub>，此时可以攻击P<sub>0</sub><sub>，0</sub>。共得到能源收益为：(-5)+20+10=25。</p><p>注意：位置（2，1）被植物P<sub>2</sub><sub>，0</sub>保护，所以无法攻击第2行中的任何植物。</p><p> </p><p>【数据规模和约定】</p><p>对于20%的数据，满足：1&lt;=N，M&lt;=5；</p><p>对于40%的数据，满足：1&lt;=N，M&lt;=10；</p><p>对于100%的数据，满足：1&lt;=N&lt;=20，1&lt;=M&lt;=30，-10000&lt;=Score&lt;=10000。</p>
</div>
</div>