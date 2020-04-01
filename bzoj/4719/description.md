
# Description

<div class="content"><div>小c同学认为跑步非常有趣,于是决定制作一款叫做《天天爱跑步》的游戏。?天天爱跑步?是一个养成类游戏,需要</div>
<div>玩家每天按时上线,完成打卡任务。这个游戏的地图可以看作一一棵包含 N个结点和N-1 条边的树, 每条边连接两</div>
<div>个结点,且任意两个结点存在一条路径互相可达。树上结点编号为从1到N的连续正整数。现在有个玩家,第个玩家的</div>
<div>起点为Si ,终点为Ti  。每天打卡任务开始时,所有玩家在第0秒同时从自己的起点出发, 以每秒跑一条边的速度,</div>
<div>不间断地沿着最短路径向着自己的终点跑去, 跑到终点后该玩家就算完成了打卡任务。 (由于地图是一棵树, 所以</div>
<div>每个人的路径是唯一的)小C想知道游戏的活跃度, 所以在每个结点上都放置了一个观察员。 在结点的观察员会选</div>
<div>择在第Wj秒观察玩家, 一个玩家能被这个观察员观察到当且仅当该玩家在第Wj秒也理到达了结点J  。 小C想知道</div>
<div>每个观察员会观察到多少人?注意: 我们认为一个玩家到达自己的终点后该玩家就会结束游戏, 他不能等待一 段时</div>
<div>间后再被观察员观察到。 即对于把结点J作为终点的玩家: 若他在第Wj秒重到达终点,则在结点J的观察员不能观察</div>
<div>到该玩家;若他正好在第Wj秒到达终点,则在结点的观察员可以观察到这个玩家。</div></div>

# Input

<div class="content"><div>第一行有两个整数N和M 。其中N代表树的结点数量, 同时也是观察员的数量, M代表玩家的数量。</div>
<div>接下来n-1 行每行两个整数U和V ,表示结点U 到结点V 有一条边。</div>
<div>接下来一行N 个整数,其中第个整数为Wj , 表示结点出现观察员的时间。</div>
<div>接下来 M行,每行两个整数Si和Ti,表示一个玩家的起点和终点。</div>
<div>对于所有的数据,保证 。</div>
<div>1&lt;=Si,Ti&lt;=N,0&lt;=Wj&lt;=N</div>
<div></div></div>

# Output

<div class="content"><p>输出1行N 个整数,第个整数表示结点的观察员可以观察到多少人。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
2 3<br/>
1 2<br/>
1 4<br/>
4 5<br/>
4 6<br/>
0 2 5 1 2 3<br/>
1 5<br/>
1 3<br/>
2 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 0 0 1 1 1</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div>对于1号点，W1=0，故只有起点为1号点的玩家才会被观察到，所以玩家1和玩家2被观察到，共2人被观察到。</div><br/>
<div>对于2号点，没有玩家在第2秒时在此结点，共0人被观察到。</div><br/>
<div>对于3号点，没有玩家在第5秒时在此结点，共0人被观察到。</div><br/>
<div>对于4号点，玩家1被观察到，共1人被观察到。</div><br/>
<div>对于5号点，玩家1被观察到，共1人被观察到。</div><br/>
<div>对于6号点，玩家3被观察到，共1人被观察到</div><br/>
</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

