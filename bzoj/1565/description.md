
# Description

<div class="content"><div>Plants vs. Zombies（PVZ）是最近十分风靡的一款小游戏。Plants（植物）和Zombies（僵尸）是游戏的主角，其</div>
<div>中Plants防守，而Zombies进攻。该款游戏包含多种不同的挑战系列，比如Protect Your Brain、Bowling等等。其</div>
<div>中最为经典的，莫过于玩家通过控制Plants来防守Zombies的进攻，或者相反地由玩家通过控制Zombies对Plants发</div>
<div>起进攻。</div>
<div></div>
<div>现在，我们将要考虑的问题是游戏中Zombies对Plants的进攻，请注意，本题中规则与实际游戏有所不同。游戏中</div>
<div>有两种角色，Plants和Zombies，每个Plant有一个攻击位置集合，它可以对这些位置进行保护；而Zombie进攻植物</div>
<div>的方式是走到植物所在的位置上并将其吃掉。</div>
<div></div>
<div>游戏的地图可以抽象为一个N行M列的矩阵，行从上到下用0到N–1编号，列从左到右用0到M–1编号；在地图的每个</div>
<div>位置上都放有一个Plant，为简单起见，我们把位于第r行第c列的植物记为Pr, c。</div>
<div></div>
<div>Plants分很多种，有攻击类、防守类和经济类等等。为了简单的描述每个Plant，定义Score和Attack如下：</div>
<div></div>
<div>Score[Pr, c]</div>
<div></div>
<div>Zombie击溃植物Pr, c可获得的能源。若Score[Pr, c]为非负整数，则表示击溃植物Pr, c可获得能源Score[Pr, c]</div>
<div>，若为负数表示击溃Pr, c需要付出能源 -Score[Pr, c]。</div>
<div></div>
<div>Attack[Pr, c]</div>
<div></div>
<div>植物Pr, c能够对Zombie进行攻击的位置集合。</div>
<div></div>
<div>Zombies必须从地图的右侧进入，且只能沿着水平方向进行移动。Zombies攻击植物的唯一方式就是走到该植物所在</div>
<div>的位置并将植物吃掉。因此Zombies的进攻总是从地图的右侧开始。也就是说，对于第r行的进攻，Zombies必须首</div>
<div>先攻击Pr, M-1；若需要对Pr, c（0 ≤ c &lt; M-1）攻击，必须将Pr,M-1, Pr, M-2 … Pr, c+1先击溃，并移动到位</div>
<div>置(r, c)才可进行攻击。</div>
<div></div>
<div>在本题的设定中，Plants的攻击力是无穷大的，一旦Zombie进入某个Plant的攻击位置，该Zombie会被瞬间消灭，</div>
<div>而该Zombie没有时间进行任何攻击操作。因此，即便Zombie进入了一个Plant所在的位置，但该位置属于其他植物</div>
<div>的攻击位置集合，则Zombie会被瞬间消灭而所在位置的植物则安然无恙（在我们的设定中，Plant的攻击位置不包</div>
<div>含自身所在位置，否则你就不可能击溃它了）。</div>
<div></div>
<div>Zombies的目标是对Plants的阵地发起进攻并获得最大的能源收入。每一次，你可以选择一个可进攻的植物进行攻</div>
<div>击。本题的目标为，制定一套Zombies的进攻方案，选择进攻哪些植物以及进攻的顺序，从而获得最大的能源收入</div>
<div>。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个整数N, M，分别表示地图的行数和列数。</div>
<div>接下来N×M行描述每个位置上植物的信息。第r×M + c + 1行按照如下格式给出植物Pr, c的信息：</div>
<div>第一个整数为Score[Pr, c], 第二个整数为集合Attack[Pr, c]中的位置个数w，</div>
<div>接下来w个位置信息（r’, c’），表示Pr, c可以攻击位置第r’ 行第c’ 列。</div>
<div>1 ≤ N ≤ 20，1 ≤ M ≤ 30，-10000 ≤ Score ≤ 10000 。</div>
<div></div>
<div></div></div>

# Output

<div class="content"><div>仅包含一个整数，表示可以获得的最大能源收入。</div>
<div>注意，你也可以选择不进行任何攻击，这样能源收入为0。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
10 0<br/>
20 0<br/>
-10 0<br/>
-5 1 0 0<br/>
100 1 2 1<br/>
100 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">25<br/>
//在样例中, 植物P1,1可以攻击位置(0,0), P2, 0可以攻击位置(2,1)。 <br/>
一个方案为，首先进攻P1,1, P0,1，此时可以攻击P0,0 。<br/>
共得到能源收益为(-5)+20+10 = 25。<br/>
注意, 位置(2,1)被植物P2,0保护，所以无法攻击第2行中的任何植物。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

