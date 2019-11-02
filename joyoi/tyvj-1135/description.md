# 

 
 # 题目背景 
虽然这么多天了,,虽然寂寞的玩了好多遍植物大战僵尸,,还是觉得写题目比控制脑残僵尸比较好玩` 

 
 # 题目描述 
植物大战僵尸<BR>&nbsp;&nbsp;&nbsp;&nbsp;【问题描述】<BR>Plants&nbsp;vs.&nbsp;Zombies（PVZ）是最近十分风靡的一款小游戏。Plants（植物）和Zombies（僵尸）是游戏的主角，其中Plants防守，而Zombies进攻。该款游戏包含多种不同的挑战系列，比如Protect&nbsp;Your&nbsp;Brain、Bowling等等。其中最为经典的，莫过于玩家通过控制Plants来防守Zombies的进攻，或者相反地由玩家通过控制Zombies对Plants发起进攻。<BR><BR>现在，我们将要考虑的问题是游戏中Zombies对Plants的进攻，请注意，本题中规则与实际游戏有所不同。游戏中有两种角色，Plants和Zombies，每个Plant有一个攻击位置集合，它可以对这些位置进行保护；而Zombie进攻植物的方式是走到植物所在的位置上并将其吃掉。<BR>游戏的地图可以抽象为一个N行M列的矩阵，行从上到下用0到N–1编号，列从左到右用0到M–1编号；在地图的每个位置上都放有一个Plant，为简单起见，我们把位于第r行第c列的植物记为Pr,&nbsp;c。<BR><BR>Plants分很多种，有攻击类、防守类和经济类等等。为了简单的描述每个Plant，定义Score和Attack如下：<BR><BR>Score[Pr,&nbsp;c]	Zombie击溃植物Pr,&nbsp;c可获得的能源。若Score[Pr,&nbsp;c]为非负整数，则表示击溃植物Pr,&nbsp;c可获得能源Score[Pr,&nbsp;c]，若为负数表示击溃Pr,&nbsp;c需要付出能源&nbsp;-Score[Pr,&nbsp;c]。<BR>Attack[Pr,&nbsp;c]	植物Pr,&nbsp;c能够对Zombie进行攻击的位置集合。<BR><BR>Zombies必须从地图的右侧进入，且只能沿着水平方向进行移动。Zombies攻击植物的唯一方式就是走到该植物所在的位置并将植物吃掉。因此Zombies的进攻总是从地图的右侧开始。也就是说，对于第r行的进攻，Zombies必须首先攻击Pr,&nbsp;M-1；若需要对Pr,&nbsp;c（0≤c&lt;M-1）攻击，必须将Pr,M-1,&nbsp;Pr,&nbsp;M-2&nbsp;…&nbsp;Pr,&nbsp;c+1先击溃，并移动到位置(r,&nbsp;c)才可进行攻击。<BR><BR><BR>在本题的设定中，Plants的攻击力是无穷大的，一旦Zombie进入某个Plant的攻击位置，该Zombie会被瞬间消灭，而该Zombie没有时间进行任何攻击操作。因此，即便Zombie进入了一个Plant所在的位置，但该位置属于其他植物的攻击位置集合，则Zombie会被瞬间消灭而所在位置的植物则安然无恙（在我们的设定中，Plant的攻击位置不包含自身所在位置，否则你就不可能击溃它了）。<BR>Zombies的目标是对Plants的阵地发起进攻并获得最大的能源收入。每一次，你可以选择一个可进攻的植物进行攻击。本题的目标为，制定一套Zombies的进攻方案，选择进攻哪些植物以及进攻的顺序，从而获得最大的能源收入。<BR><BR> 

 
 # 输入格式 
【输入文件】<BR>输入文件pvz.in的第一行包含两个整数N,&nbsp;M，分别表示地图的行数和列数。<BR>接下来N×M行描述每个位置上植物的信息。第r×M&nbsp;+&nbsp;c&nbsp;+&nbsp;1行按照如下格式给出植物Pr,&nbsp;c的信息：第一个整数为Score[Pr,&nbsp;c],&nbsp;第二个整数为集合Attack[Pr,&nbsp;c]中的位置个数w，接下来w个位置信息（r’,&nbsp;c’），表示Pr,&nbsp;c可以攻击位置第r’&nbsp;行第c’&nbsp;列。 

 
 # 输出格式 
【输出文件】<BR>输出文件pvz.out仅包含一个整数，表示可以获得的最大能源收入。注意，你也可以选择不进行任何攻击，这样能源收入为0。<BR> 

 
 # 提示 
【样例说明】<BR>在样例中,&nbsp;植物P1,1可以攻击位置(0,0),&nbsp;P2,&nbsp;0可以攻击位置(2,1)。<BR>一个方案为，首先进攻P1,1,&nbsp;P0,1，此时可以攻击P0,0&nbsp;。共得到能源收益为(-5)+20+10&nbsp;=&nbsp;25。注意,&nbsp;位置(2,1)被植物P2,0保护，所以无法攻击第2行中的任何植物。<BR><BR><BR>【大致数据规模】<BR>约20%的数据满足1&nbsp;≤&nbsp;N,&nbsp;M&nbsp;≤&nbsp;5；<BR>约40%的数据满足1&nbsp;≤&nbsp;N,&nbsp;M&nbsp;≤&nbsp;10；<BR>约100%的数据满足1&nbsp;≤&nbsp;N&nbsp;≤&nbsp;20，1&nbsp;≤&nbsp;M&nbsp;≤&nbsp;30，-10000&nbsp;≤&nbsp;Score&nbsp;≤&nbsp;10000<BR>noi2009&nbsp;day2&nbsp;problem1 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3 2
10 0
20 0
-10 0
-5 1 0 0
100 1 2 1
100 0
</td><td>25</td></tr></table>
