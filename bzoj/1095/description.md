
# Description

<div class="content"><p>　　捉迷藏 Jiajia和Wind是一对恩爱的夫妻，并且他们有很多孩子。某天，Jiajia、Wind和孩子们决定在家里玩<br/>
捉迷藏游戏。他们的家很大且构造很奇特，由N个屋子和N-1条双向走廊组成，这N-1条走廊的分布使得任意两个屋<br/>
子都互相可达。游戏是这样进行的，孩子们负责躲藏，Jiajia负责找，而Wind负责操纵这N个屋子的灯。在起初的<br/>
时候，所有的灯都没有被打开。每一次，孩子们只会躲藏在没有开灯的房间中，但是为了增加刺激性，孩子们会要<br/>
求打开某个房间的电灯或者关闭某个房间的电灯。为了评估某一次游戏的复杂性，Jiajia希望知道可能的最远的两<br/>
个孩子的距离（即最远的两个关灯房间的距离）。 我们将以如下形式定义每一种操作： C(hange) i 改变第i个房<br/>
间的照明状态，若原来打开，则关闭；若原来关闭，则打开。 G(ame) 开始一次游戏，查询最远的两个关灯房间的<br/>
距离。</p></div>

# Input

<div class="content"><p>　　第一行包含一个整数N，表示房间的个数，房间将被编号为1,2,3…N的整数。接下来N-1行每行两个整数a, b，<br/>
表示房间a与房间b之间有一条走廊相连。接下来一行包含一个整数Q，表示操作次数。接着Q行，每行一个操作，如<br/>
上文所示。</p></div>

# Output

<div class="content"><p>　　对于每一个操作Game，输出一个非负整数到hide.out，表示最远的两个关灯房间的距离。若只有一个房间是关<br/>
着灯的，输出0；若所有房间的灯都开着，输出-1。</p></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
1 2<br/>
2 3<br/>
3 4<br/>
3 5<br/>
3 6<br/>
6 7<br/>
6 8<br/>
7<br/>
G<br/>
C 1<br/>
G<br/>
C 2<br/>
G<br/>
C 1<br/>
G</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
3<br/>
3<br/>
4</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据， N ≤100000, M ≤500000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

